# Panduan Admin — Materi Malaka

## Upload materi setelah menu terpasang

1. Masuk ke GitHub memakai akun yang memiliki izin mengubah repositori.
2. Buka https://github.com/marlon-jacob/raimalakadiak-malaka dan pilih branch main.
3. Klik folder **materi-malaka**.
4. Klik **Add file → Upload files → choose your files**.
5. Pilih materi dari komputer. Format yang ditampilkan: PDF, PPT/PPTX, DOC/DOCX, XLS/XLSX. Gunakan nama sederhana, misalnya **01-panduan-pembelajaran-malaka.pdf**. Nomor di depan mengatur urutan daftar.
6. Tulis pesan, misalnya **Tambah materi pelatihan Malaka**, lalu klik **Commit changes**. Jika GitHub meminta cabang baru/pull request, perubahan harus digabung ke main sebelum tampil.
7. Tunggu penerbitan GitHub Pages selesai. Buka https://marlon-jacob.github.io/raimalakadiak-malaka/ → **Materi SPP → Materi Malaka**. Coba **Lihat** dan **Unduh**.

Admin tidak perlu mengedit index.html atau menambah daftar judul. Judul dibentuk dari nama file. Simpan file langsung di materi-malaka, bukan di subfolder. README.md tidak ditampilkan sebagai materi.

## Mengganti materi

Upload file baru dengan nama yang persis sama ke folder materi-malaka, lalu simpan perubahan. Gunakan nama baru jika ingin mempertahankan dua versi. Periksa hasilnya melalui situs setelah penerbitan selesai.

## Jika materi belum terlihat

- Pastikan file ada di branch main, langsung di folder materi-malaka, dengan format yang didukung.
- Muat ulang halaman. Periksa tab Actions di repositori jika penerbitan belum selesai.
- Jika muncul pesan gagal memuat, klik **Coba lagi** atau **Buka folder materi**. Daftar otomatis memerlukan koneksi internet dan GitHub API; pembatasan sementara API dapat membuat daftar gagal dimuat.
- Jika pratinjau Word/Excel/PowerPoint gagal, gunakan **Unduh** dan buka di komputer.
- Upload melalui browser dibatasi 25 MiB per file. Perkecil file yang terlalu besar.

Rujukan upload: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

## Pemasangan awal — cukup sekali

Paket ini disiapkan dari ZIP GitHub yang diberikan pengguna pada 2 November 2026. index.html dalam ZIP identik dengan dasar perubahan, sehingga pembaruan menu cocok dengan versi tersebut. Paket belum diunggah ke GitHub.

1. Ekstrak ZIP siap-upload-materi-malaka.zip di komputer.
2. Buka https://github.com/marlon-jacob/raimalakadiak-malaka/upload/main dan pastikan sudah login.
3. Dari folder hasil ekstrak, seret **index.html**, folder **materi-malaka**, dan **PANDUAN-ADMIN.md** ke area upload GitHub. Jangan upload file ZIP atau folder pembungkus siap-upload-materi-malaka.
4. Periksa bahwa GitHub menampilkan index.html di tingkat utama dan materi-malaka/README.md di dalam folder materi-malaka. File index.html lama akan diperbarui; materi SPP lama tetap ada.
5. Isi pesan **Tambah menu Materi Malaka**. Pilih menyimpan ke main jika tersedia, lalu klik **Commit changes**. Jika diwajibkan membuat pull request, gabungkan perubahan ke main sesuai alur repositori.
6. Tunggu penerbitan di tab **Actions** selesai. Buka https://marlon-jacob.github.io/raimalakadiak-malaka/?v=materi-malaka-20261102 lalu pilih Materi SPP. Menu baru berada setelah SPP 3. Saat bahasa EN aktif, namanya **Malaka Materials**.
7. Klik menu baru. Pesan belum ada materi adalah normal sebelum admin mengupload dokumen pertama. Upload satu dokumen yang benar melalui langkah di bagian awal panduan, lalu uji tombol Lihat dan Unduh.

Jika ada perubahan GitHub setelah ZIP ini diunduh, bandingkan index.html terlebih dahulu sebelum upload. Tidak perlu mengunggah ulang file SPP yang lama.

## Pemeriksaan

Versi dasar cocok persis dengan index.html dalam ZIP terbaru pengguna. Sintaks dua skrip halaman lulus. Fungsi daftar sudah diuji memakai data contoh untuk filter format, nama file berspasi, bahasa ID/EN, daftar kosong, kegagalan API, dan perpindahan kategori saat pemuatan berlangsung. Tampilan browser dan situs publik belum diverifikasi.
