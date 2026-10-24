# Aplikasi Generator Nota Pintar (Vercel + GitHub Database)

Aplikasi web modern untuk pembuatan nota otomatis dengan fitur sinkronisasi logo, cetak PDF, dan penyimpanan langsung ke repository GitHub sebagai database tanpa server backend tambahan.

## Fitur Utama
1. **Generator Nota Otomatis**: Kelola item barang, diskon, dan pajak PPN secara instan.
2. **Sinkronisasi Logo Toko**: Unggah atau masukkan URL logo toko yang otomatis terpasang secara *real-time* di panel dan pratinjau nota.
3. **Cetak & Unduh PDF**: Format cetak bersih dan rapi menggunakan fitur print bawaan browser ke PDF.
4. **Database GitHub**: Simpan data nota secara aman langsung ke repository GitHub menggunakan Personal Access Token (PAT).
5. **Siap Vercel (Vercel Ready)**: Dapat di-deploy dalam hitungan detik ke Vercel sebagai aplikasi statis.

## Cara Deploy ke Vercel
1. Upload folder project ini ke repository GitHub Anda.
2. Buka [Vercel Dashboard](https://vercel.com), klik **Add New Project**, lalu import repository GitHub Anda.
3. Vercel akan mendeteksi sebagai static site dan siap di-deploy secara otomatis!

## Cara Pengaturan Database GitHub
1. Buat Personal Access Token (PAT) di GitHub dengan scope `repo`.
2. Di aplikasi NotaPro, klik tombol **Koneksi GitHub**.
3. Masukkan Username, Nama Repository, dan Token Anda.
4. Data nota Anda akan langsung tersimpan di folder `notas/` di repository GitHub Anda setiap kali Anda menekan tombol "Simpan ke GitHub".
