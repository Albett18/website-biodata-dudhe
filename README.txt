WEBSITE BIODATA — DUDHE ADDULLOH AJI PERMADI

CARA MENJALANKAN
1. Ekstrak file ZIP.
2. Buka folder biodata_dudhe.
3. Klik dua kali index.html untuk membukanya di browser.
4. Website tidak membutuhkan instalasi Python atau database.

CARA MEMASANG FOTO PRIBADI
1. Buka folder images.
2. Simpan foto pribadi di folder tersebut dengan nama profile.jpg.
3. Buka index.html, cari baris:
   <img id="profileImage" src="images/profile-placeholder.svg" alt="Placeholder foto profil Dudhe">
4. Ganti menjadi:
   <img id="profileImage" src="images/profile.jpg" alt="Foto profil Dudhe">
5. Simpan, lalu refresh browser.

LINK MEDIA SOSIAL
Instagram: https://www.instagram.com/18dudhe_/
TikTok: https://www.tiktok.com/@albertcamaron
YouTube: https://www.youtube.com/@itsmeisalbert
Saweria: https://saweria.co/CAMARON

FILE
- index.html : struktur dan konten website
- style.css  : desain, warna, layout responsif
- script.js  : menu HP dan menu navigasi aktif
- images/profile-placeholder.svg : gambar sementara untuk profil

Catatan: Google Fonts membutuhkan koneksi internet; font fallback tetap tersedia jika offline.


CARA MENGAKTIFKAN KOMENTAR PUBLIK (GISCUS — GRATIS)
PENTING: Kolom komentar sudah ditambahkan ke desain, tetapi belum bisa menerima komentar sampai kamu menghubungkannya ke GitHub. Giscus menyimpan komentar di GitHub Discussions; pengunjung harus masuk/otorisasi dengan akun GitHub untuk berkomentar.

1. Buat atau gunakan akun GitHub, lalu buat REPOSITORY BARU yang PUBLIC (jangan masukkan password atau data pribadi ke repository).
2. Di pengaturan repository, aktifkan fitur Discussions.
3. Buka https://github.com/apps/giscus lalu install aplikasi Giscus pada repository tersebut.
4. Buka https://giscus.app/ dan masukkan nama repository dengan format pemilik/nama-repo. Pilih mapping “Discussion title contains page pathname” dan kategori diskusi yang sesuai.
5. Di bagian bawah halaman giscus.app, salin script <script ...> yang dibuat otomatis.
6. Buka index.html dan cari komentar HTML: <!-- TEMPEL KODE GISCUS DI SINI -->. Ganti komentar itu dengan script Giscus yang kamu salin, lalu simpan. (Jika penanda belum ada, letakkan script tepat setelah <div id="giscus-comments" class="giscus"></div>.)
7. Upload ulang folder biodata_dudhe ke Netlify. Tes website publik kamu. Komentar yang masuk bisa dimoderasi melalui GitHub Discussions.

Panduan resmi: https://giscus.app/ dan https://github.com/giscus/giscus
