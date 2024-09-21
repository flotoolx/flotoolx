# FloToolX - Easy Create Video ⚡

## Deskripsi Produk
FloToolX - Easy Create Video adalah aplikasi desktop yang powerful untuk Windows dan Mac. Aplikasi ini memungkinkan pengguna untuk menghasilkan video berkualitas tinggi dengan mudah, lengkap dengan teks dan gambar sesuai input pengguna.

## Persyaratan Sistem
- Sistem Operasi: Windows atau macOS (Ventura/Sonoma)
- Aplikasi Pendukung:
  - HomeBrew (untuk macOS)
  - ImageMagick
  - ffmpeg

## Panduan Instalasi

### Windows
1. Unduh file `FloToolX.zip`
2. Ekstrak file zip tersebut
3. Jalankan aplikasi dengan mengklik dua kali pada `FloToolX.exe`

### macOS

#### 1. Instalasi Homebrew
1. Buka Terminal
2. Salin dan tempel perintah berikut:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
3. Ikuti instruksi yang muncul di layar

#### 2. Instalasi ImageMagick
1. Di Terminal, jalankan perintah:
   ```bash
   brew install imagemagick
   ```

#### 3. Instalasi FFmpeg
1. Di Terminal, jalankan perintah:
   ```bash
   brew install ffmpeg
   ```

#### 4. Instalasi FloToolX-ShortVideo
1. Unduh file `FloToolX-VideoApp.app`
2. Pindahkan `FloToolX-VideoApp.app` ke folder **Applications**
3. Salin folder **FloToolX-VideoApp** ke direktori `/Users/[NamaProfil]`
4. Jalankan aplikasi dengan mengklik dua kali ikon **FloToolX-VideoApp** di folder **Applications** atau **Launchpad**

## Penggunaan Dasar
1. Persiapkan file subtitle di folder "subtitle"
2. Siapkan gambar di folder "images"
3. Jalankan VideoApp.exe (Windows) atau VideoApp.app (macOS)

## Catatan
Untuk hasil optimal, pastikan penamaan file di folder subtitle dan image konsisten:
- Subtitle: subtitle_1.txt, subtitle_2.txt, dst.
- Gambar: image_1.jpg atau image_1.png, image_2.jpg atau image_2.png, dst.

### Menambahkan Subtitle
1. Buka folder Addons > contoh.txt
2. Salin teks atau hook yang telah Anda siapkan ke dalam file contoh.txt
3. Jalankan buat_text.exe
4. File hasil akan tersimpan di folder subtitle
5. Salin folder subtitle ke lokasi yang sama dengan file .exe

### Menambahkan Font Kustom
1. Unduh font dari https://fonts.google.com
2. Salin file font ke folder "fonts"

## Troubleshooting

### Jika perintah 'brew' tidak ditemukan (macOS):
Jalankan perintah berikut di Terminal:
```bash
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/[NamaProfil]/.zprofile && eval "$(/opt/homebrew/bin/brew shellenv)"
```
Ganti [NamaProfil] dengan nama profil Mac Anda.

### Jika muncul pesan "FloToolX-VideoApp cannot be opened because the developer cannot be verified":
1. Buka "System Preferences" > "Security & Privacy" > tab "General"
2. Klik "Open Anyway" di sebelah pesan tentang FloToolX-VideoApp
3. Atau, klik kanan (Control-click) pada FloToolX-VideoApp.app > Pilih "Open" > Klik "Open" pada dialog keamanan

## Informasi Tambahan
- Versi Terkini: v1.0.1
- Pengembang: FloToolX


📫 Jika Anda mengalami masalah atau memiliki pertanyaan lebih lanjut, silakan hubungi kami.

