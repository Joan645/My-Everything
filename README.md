# My Soul, My World, and My Everything

Website statis satu halaman untuk MVP.

## Jalankan di komputer

1. Install Node.js.
2. Buka terminal di folder proyek.
3. Jalankan `npm install`.
4. Jalankan `npm start`.
5. Buka alamat lokal yang ditampilkan di terminal.

## Upload ke GitHub

Buat repository baru di GitHub (misalnya `my-soul-my-world`), lalu dari terminal di folder ini jalankan:

```bash
git init
git add .
git commit -m "Initial website MVP"
git branch -M main
git remote add origin https://github.com/USERNAME/my-soul-my-world.git
git push -u origin main
```

Ganti `USERNAME` dengan username GitHub kamu. Jika Git meminta autentikasi, ikuti proses login yang ditampilkan.

## Deploy ke Railway

1. Login ke https://railway.app menggunakan GitHub.
2. Pilih **New Project** → **Deploy from GitHub repo**.
3. Pilih repository `my-soul-my-world`.
4. Railway akan membaca `package.json` dan menjalankan script `start`.
5. Setelah deployment selesai, buka **Settings** pada service → **Networking** → **Generate Domain** (nama menu dapat berubah).
6. Gunakan domain `.up.railway.app` yang diberikan sebagai link website.

Catatan: Railway dapat meminta verifikasi atau detail billing sesuai kebijakan akun dan wilayah. Pastikan cek informasi harga Railway terbaru sebelum deploy.
