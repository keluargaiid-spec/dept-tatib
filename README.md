# Sistem Monitoring Tatib Kursi Pertemuan

Sistem aplikasi web berbasis **Firebase Realtime Database** untuk memantau kapasitas dan status keterisian kursi dalam perhelatan/seminar secara *real-time*.

##  Fitur Utama
- **Realtime Synchronization**: Perubahan data di HP Operator langsung tampil instan pada layar TV / HDMI.
- **PIN Security Keypad**: Fitur penting (Tambah/Hapus/Setting Penuh) dilindungi kode PIN.
- **Lock Mode**: Mencegah salah tekan posisi kursi saat pengawasan acara berlangsung.
- **Mobile Optimized**: Bebas kendala *click-delay* pada browser seluler (Android/iOS).

##  Pin Default
- **Tambah / Hapus Blok**: `1234`
- **Set Penuh / Kosong Blok**: `5678`

##  Cara Deploy ke GitHub Pages
1. Buat repository baru di GitHub (misal: `monitoring-tatib`).
2. Unggah ketiga file berikut ke repository:
   - `index.html`
   - `operator.html`
   - `display.html`
3. Masuk ke **Settings** > **Pages**.
4. Pada opsi **Source**, pilih `Deploy from a branch` lalu pilih branch `main` (atau `master`) dan folder `/ (root)`.
5. Klik **Save**. Web App siap diakses melalui tautan GitHub Pages Anda.
