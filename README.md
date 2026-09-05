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
</p>

---

## 📥 Unduh Installer (Versi Terbaru)

Silakan unduh installer sesuai dengan sistem operasi perangkat Anda di bawah ini atau melalui halaman [**Releases**](https://github.com/Stromzzz/fotospace-releases/releases/latest):

| Sistem Operasi | Tipe File | Rekomendasi Unduhan | Keterangan |
| :--- | :--- | :--- | :--- |
| **Windows** (64-bit) | `.exe` | [**`foto-space-1.2.1-setup.exe`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1-setup.exe) | **Installer Wizard (Desktop & Start Menu Shortcut)** |
| **macOS** (Apple Silicon) | `.dmg` | [**`foto-space-1.2.1-arm64.dmg`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1-arm64.dmg) | Untuk Mac M1, M2, M3, M4 Series |
| **macOS** (Intel) | `.dmg` | [**`foto-space-1.2.1-x64.dmg`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1-x64.dmg) | Untuk Mac berbasis prosesor Intel x64 |
| **Linux** (Universal) | `.AppImage` | [**`foto-space-1.2.1.AppImage`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1.AppImage) | Mandiri tanpa instalasi (Ubuntu, Debian, Fedora, Arch) |

---

## 🛠️ Panduan Instalasi & Menjalankan

### 1. Windows
1. Unduh file [**`foto-space-1.2.1-setup.exe`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1-setup.exe).
2. Klik ganda file `.exe` dan ikuti wizard instalasi.
3. *Catatan Windows SmartScreen:* Jika muncul peringatan *"Windows protected your PC"*, klik **More info** $\rightarrow$ klik **Run anyway**.

### 2. macOS
1. Unduh file `.dmg` yang sesuai dengan arsitektur Mac Anda:
   - **Apple Silicon (M1/M2/M3/M4)**: gunakan file dengan akhiran `-arm64.dmg`.
   - **Intel**: gunakan file dengan akhiran `-x64.dmg`.
2. Buka file `.dmg` hasil unduhan.
3. **PENTING (Instalasi)**: **Seret (drag & drop)** ikon **Foto Space** ke folder **Applications** di sebelahnya.
   - *Catatan*: Jangan double-click *"Uninstall Foto Space"* di dalam DMG jika ingin menginstal aplikasi.
4. Buka **Foto Space** dari folder **Applications**.
5. *Jika muncul peringatan Gatekeeper macOS ("tidak dapat dibuka karena tidak diunduh dari App Store" / "pengembang tidak teridentifikasi")*:
   - **Cara 1 (System Settings - Rekomendasi macOS Ventura/Sonoma/Sequoia)**:
     1. Buka **Pengaturan Sistem (System Settings)** $\rightarrow$ **Privasi & Keamanan (Privacy & Security)**.
     2. Pada bagian *Keamanan*, pastikan opsi disetel ke **"App Store dan pengembang teridentifikasi"**.
     3. Cari notifikasi *"Foto Space diblokir..."* lalu klik tombol **Tetap Buka (Open Anyway)**.
     4. Masukkan password Mac / Touch ID lalu pilih **Buka (Open)**.
   - **Cara 2 (Terminal - Cepat & Langsung Berhasil)**:
     Buka aplikasi **Terminal**, jalankan perintah berikut lalu tekan Enter:
     ```bash
     xattr -cr "/Applications/Foto Space"*
     ```
     *(Cukup gunakan nama aplikasi **Foto Space**, tanda `*` otomatis mengenali aplikasi di macOS).*
   - **Cara 3 (Finder)**:
     Buka folder **Applications** $\rightarrow$ Klik kanan (Control + Klik) pada icon **Foto Space** $\rightarrow$ pilih **Buka (Open)** $\rightarrow$ klik **Buka**.

### 3. Linux
1. Unduh file [**`foto-space-1.2.1.AppImage`**](https://github.com/Stromzzz/fotospace-releases/releases/download/v1.2.1/foto-space-1.2.1.AppImage).
2. Berikan izin eksekusi melalui terminal atau file manager:
   ```bash
   chmod +x foto-space-1.2.1.AppImage
   ./foto-space-1.2.1.AppImage
   ```

---

## ✨ Fitur Utama (v1.2.1)

- **Upload Foto & Video ke FotoYu**: Pilih folder lewat dialog sistem OS, scan, lalu unggah ke galeri.
- **Kompresi Hemat (default 50%)**: Perkecil foto otomatis agar hemat kuota; preset Hemat / Seimbang / Tajam + slider persen.
- **Orientasi otomatis**: Portrait & landscape di folder campuran mengikuti file asli (EXIF / rotasi video).
- **Dukungan Video**: Transcode & ekstraksi frame ZIP sesuai batas FotoYu (maks ~4 detik).
- **Pembaruan Otomatis (Auto-Update)**: Notifikasi dan unduhan pembaruan langsung di dalam aplikasi.
- **Form Kritik & Saran (Feedback)**: Kirim laporan kendala atau masukan fitur dari sidebar.
- **Proteksi Lisensi Perangkat**: Aktivasi aman berbasis kunci lisensi terenkripsi.

---

## 🔄 Feed Auto-Update (Internal)

Repository ini juga berfungsi sebagai endpoint distribusi pembaruan otomatis aplikasi:
- **Windows Feed**: `latest.yml`
- **Linux Feed**: `latest-linux.yml`
- **macOS Feed**: `latest-mac.yml`
- **Differential Update Maps**: `*.blockmap` (menghemat kuota dengan hanya mengunduh data biner yang berubah).

---

<p align="center">
  <sub>Copyright © 2026 Foto Space. All rights reserved.</sub>
</p>
