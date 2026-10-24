# MARKETING APK

1. Buat repo baru di GitHub (misal `marketing-app`), upload SEMUA isi folder ini (termasuk folder `.github`).
2. Buka tab **Actions** > **Build APK** > **Run workflow** (atau otomatis jalan saat upload).
3. Tunggu sekitar 5 menit, buka run yang selesai, unduh **MARKETING-apk** di bagian Artifacts.
4. Ekstrak zip-nya, kirim `app-debug.apk` ke HP, lalu instal (izinkan "instal dari sumber tidak dikenal").

Data tersimpan di penyimpanan lokal HP. Font Google butuh internet saat pertama dibuka; tanpa internet tampilan memakai font sistem.

## Sync antar perangkat (GitHub Gist)

Di menu samping ada tombol **Sync** dan **Atur**.

1. Tekan **Atur**, buat token GitHub dengan izin `gist` (link ada di dialog), tempel, lalu **Simpan & Sync**.
2. Data tersimpan sebagai file `marketing-data.json` di Gist rahasia di akun GitHub Anda.
3. Di perangkat lain, pasang APK yang sama, masukkan token yang sama, tekan **Sync**. Data otomatis dimuat dan digabung (yang paling baru diubah yang menang; tugas yang dihapus ikut terhapus).
