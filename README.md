# Planner Hub

Planner Hub adalah aplikasi perencanaan terpadu dalam satu halaman. Aplikasi ini menghubungkan pekerjaan harian dengan proyek dan planner khusus, sehingga tugas, jadwal, target, dan kebutuhan proyek dapat dikelola dalam satu workspace.

## Konsep

Setiap proyek menjadi pusat informasi yang mengaitkan brief, rentang waktu, tugas, agenda, milestone, anggota atau kontak, anggaran, dan deliverable. Tampilan khusus membantu menyesuaikan alur kerja untuk proyek kreatif, pernikahan, dan event. Data aplikasi disimpan di browser yang digunakan.

## Fitur

- **Home** — ringkasan aktivitas dan pintasan ke pekerjaan utama.
- **Today** — daftar pekerjaan untuk hari ini dan pengelolaan tugas.
- **Calendar & Tasks** — kalender untuk melihat tugas dan acara, serta rentang waktu proyek dan milestone.
- **Projects** — detail proyek, brief, status, pemilik, klien, jadwal, tugas, agenda, dan sumber daya terkait.
- **Planners** — area planner untuk kebutuhan harian, mingguan, bulanan, dan kategori khusus.
- **Creative** — pengelolaan project brief, objective, scope, deliverable, timeline, dan pekerjaan kreatif.
- **Wedding** — pengelolaan daftar tamu, vendor, anggaran, tugas, dan timeline acara.
- **Event / EO** — perencanaan event yang mencakup rundown, tim, logistik, anggaran, dan pekerjaan operasional.
- **Autosave** — perubahan planner tersimpan otomatis. Draf yang belum dikirim dari form juga dipulihkan ketika halaman dimuat ulang.
- **PDF** — pratinjau dan cetak/simpan PDF dengan pengaturan orientasi, tema, ukuran teks, footer, bagian, judul, dan header tabel.
- **CSV dan JSON** — ekspor/impor CSV untuk data lintas proyek beserta pengaturan PDF, serta backup dan pemulihan data dalam format JSON.
- **Tampilan** — tema terang/gelap dan tata letak yang menyesuaikan ukuran layar.

## Menjalankan aplikasi

1. Buka `planner-revised.html` menggunakan browser modern.
2. Gunakan navigasi untuk berpindah antar-area.
3. Buat proyek atau planner, lalu hubungkan tugas, agenda, milestone, dan data pendukung sesuai kebutuhan.
4. Gunakan tombol ekspor untuk mencadangkan data atau membuat dokumen PDF.

Aplikasi tidak memerlukan proses instalasi atau server untuk penggunaan dasar. Ikon menggunakan Font Awesome dari CDN, sehingga koneksi internet diperlukan untuk memuat ikon tersebut.

## Penyimpanan data

Data planner disimpan secara lokal di browser dan profil pengguna yang sama. Data tidak otomatis tersinkron ke perangkat lain. Ekspor CSV atau JSON secara berkala untuk membuat salinan cadangan. Menghapus data situs/browser dapat menghapus data lokal aplikasi.

## File utama

- `planner-revised.html` — aplikasi Planner Hub versi revisi.
- `README.md` — konsep, fitur, dan panduan penggunaan singkat.
- `.gitignore` — daftar file lokal dan artefak yang tidak perlu dimasukkan ke Git.
