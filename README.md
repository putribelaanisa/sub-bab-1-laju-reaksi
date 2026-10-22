# Konsep Laju Reaksi dan Teori Tumbukan

Media pembelajaran kimia interaktif (SMA/MA kelas XI). Situs statis satu halaman: tidak perlu build.

## Struktur
- `index.html` : seluruh media (HTML, CSS, JavaScript dalam satu file)
- `vercel.json` : konfigurasi Vercel

## Deploy ke Vercel lewat GitHub
1. Buat repositori baru di GitHub, lalu unggah ketiga file ini ke branch `main`.
2. Buka vercel.com, login dengan akun GitHub, klik **Add New → Project**.
3. Pilih repositori tadi lalu klik **Import**.
4. Pengaturan: Framework Preset **Other**, Build Command dan Output Directory dikosongkan, Root Directory `./`.
5. Klik **Deploy**. Setelah selesai Anda mendapat alamat `https://nama-proyek.vercel.app`.
6. Setiap `git push` ke `main` akan otomatis memperbarui situs.
