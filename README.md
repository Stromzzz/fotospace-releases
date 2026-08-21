# Foto Space — Official Releases & Downloads

<p align="center">
  <img src="assets/logo.png" width="128" height="128" alt="Foto Space Logo" />
</p>

<p align="center">
  <strong>Aplikasi Desktop Otomasi & Manajemen Upload Foto & Video ke FotoYu</strong>
</p>

<p align="center">
  <a href="https://github.com/Stromzzz/fotospace-releases/releases/latest"><img src="https://img.shields.io/github/v/release/Stromzzz/fotospace-releases?label=Latest%20Version&color=blue" alt="Latest Release" /></a>
  <img src="https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux-success" alt="Platforms" />
  <img src="https://img.shields.io/badge/Electron-v33-orange" alt="Electron" />
</p>

---

## 📥 Unduh Installer (Versi Terbaru)

Silakan unduh installer sesuai dengan sistem operasi perangkat Anda di bawah ini atau melalui halaman [**Releases**](https://github.com/Stromzzz/fotospace-releases/releases/latest):

| Sistem Operasi | Tipe File | Rekomendasi Unduhan | Keterangan |
| :--- | :--- | :--- | :--- |
| **Windows** (64-bit) | `.exe` | [**`foto-space-1.1.7-setup.exe`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-setup.exe) | **Installer Wizard (Desktop & Start Menu Shortcut)** |
| **Windows** (Portable) | `.7z` | [**`foto-space-1.1.7-setup.7z`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-setup.7z) | Format portable kompresi tinggi (LZMA2 solid) |
| **Windows** (Portable) | `.zip` | [**`foto-space-1.1.7-setup.zip`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-setup.zip) | Format portable standar Zip |
| **macOS** (Apple Silicon) | `.dmg` | [**`foto-space-1.1.7-arm64.dmg`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-arm64.dmg) | Untuk Mac M1, M2, M3, M4 Series |
| **macOS** (Intel) | `.dmg` | [**`foto-space-1.1.7-x64.dmg`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-x64.dmg) | Untuk Mac berbasis prosesor Intel x64 |
| **Linux** (Universal) | `.AppImage` | [**`foto-space-1.1.7.AppImage`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7.AppImage) | Mandiri tanpa instalasi (Ubuntu, Debian, Fedora, Arch) |

---

## 🛠️ Panduan Instalasi & Menjalankan

### 1. Windows
1. Unduh file [**`foto-space-1.1.7-setup.exe`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-setup.exe).
2. Klik ganda file `.exe` dan ikuti wizard instalasi.
3. *Catatan Windows SmartScreen:* Jika muncul peringatan *"Windows protected your PC"*, klik **More info** $\rightarrow$ klik **Run anyway**.

### 2. macOS
1. Unduh file `.dmg` yang sesuai dengan prosesor Mac Anda ([**Apple Silicon arm64**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-arm64.dmg) atau [**Intel x64**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7-x64.dmg)).
2. Buka file `.dmg`, lalu seret icon **Foto Space** ke folder **Applications**.
3. *Catatan Keamanan macOS:* Jika muncul notifikasi *"App is damaged / Unidentified Developer"*, jalankan perintah berikut di Terminal:
   ```bash
   xattr -cr /Applications/Foto\ Space.app
   ```
   Atau klik kanan pada icon Foto Space di folder Applications $\rightarrow$ pilih **Open** $\rightarrow$ klik **Open**.

### 3. Linux
1. Unduh file [**`foto-space-1.1.7.AppImage`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.1.7/foto-space-1.1.7.AppImage).
2. Berikan izin eksekusi melalui terminal atau file manager:
   ```bash
   chmod +x foto-space-1.1.7.AppImage
   ./foto-space-1.1.7.AppImage
   ```

---

## ✨ Fitur Utama (v1.1.7)

- **Otomasi Upload Foto & Video**: Monitoring folder lokal dan upload otomatis ke event/folder FotoYu.
- **Dukungan Video Cerdas**: Transcoding otomatis dan ekstraksi thumbnail video berkecepatan tinggi.
- **Pembaruan Otomatis (Auto-Update)**: Notifikasi dan unduhan pembaruan langsung di dalam aplikasi saat versi baru rilis.
- **Form Kritik & Saran (Feedback)**: Kirim laporan kendala atau masukan fitur langsung dari sidebar aplikasi.
- **Proteksi Lisensi Perangkat**: Aktivasi aman berbasis kunci lisensi terenkripsi.

---

## 🔄 Feed Auto-Update (Internal)

Repository ini juga berfungsi sebagai endpoint distribusi update otomatis untuk `electron-updater`:

- **Windows Feed**: `latest.yml`
- **Linux Feed**: `latest-linux.yml`
- **macOS Feed**: `latest-mac.yml`
- **Differential Update Maps**: `*.blockmap` (menghemat kuota dengan hanya mengunduh data biner yang berubah).

---

<p align="center">
  <sub>Copyright © 2026 Foto Space. All rights reserved.</sub>
</p>
