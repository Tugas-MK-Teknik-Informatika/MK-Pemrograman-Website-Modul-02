# Modul 2: Standardisasi Kode dan Pengorganisasian Konten Web

Repositori kerja praktikum mata kuliah Pemrograman Website, Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.

| Keterangan | Rincian |
| --- | --- |
| Mata Kuliah | Pemrograman Website |
| Modul | 2 dari 11 |
| Topik | Standardisasi Kode dan Pengorganisasian Konten Web |
| Program Studi | Teknik Informatika |
| Institusi | Fakultas Teknik, Universitas Hasanuddin |

## Deskripsi Modul

Modul ini menjamin kualitas penataan data di dalam dokumen sebelum manipulasi tampilan grafis dengan CSS. Fokus pembahasan berada pada penulisan kode yang patuh standar, pemahaman perilaku render elemen, serta pengorganisasian konten kompleks berupa tabel, daftar bertingkat, dan media berketerangan.

## Capaian Pembelajaran

Setelah menyelesaikan modul ini, mahasiswa diharapkan mampu:

1. **Menerapkan standardisasi penulisan kode**
   - Mengikuti spesifikasi W3C dalam penulisan HTML.
   - Menghasilkan kode yang bersih, valid, dan mudah dipelihara.
2. **Menganalisis perilaku render elemen**
   - Membedakan karakteristik block-level dan inline-level elements.
   - Memprediksi alur pemformatan elemen pada peramban.
3. **Mengorganisasikan konten kompleks**
   - Menyusun tabel terstruktur dan daftar bertingkat.
   - Menggunakan figure, figcaption, dan referensi karakter khusus.
4. **Merancang skema penautan halaman**
   - Membedakan penggunaan tautan relatif dan absolut.
   - Menelusuri struktur direktori berkas secara presisi.

## Cakupan Materi

- Standar W3C dan alasan menjaga peramban tetap berada pada standards mode.
- Perilaku block-level dan inline-level beserta dampaknya terhadap alur dokumen.
- Tabel semantis dengan thead, tbody, tfoot, atribut scope, colspan, dan rowspan.
- Daftar bertingkat, elemen figure dan figcaption, serta entitas karakter khusus.
- Skema penautan absolut dan relatif untuk menjaga portabilitas kode antar direktori.

## Hands-on Lab

Menyusun halaman kurikulum dan silabus yang memuat daftar bertingkat serta tabel distribusi SKS dengan penggabungan sel.

Kode hasil praktikum terbimbing pada sesi kelas disimpan di dalam repositori ini. Ikuti langkah demonstrasi yang dipandu dosen atau asisten, lalu bandingkan hasil pekerjaan Anda dengan berkas rujukan yang tersedia.

## Struktur Berkas

```
MK-Pemrograman-Website-Modul-02/
  index.html
  unhas_logo.png
```

## Petunjuk Penggunaan

### Kebutuhan Perangkat
1. Peramban modern seperti Google Chrome, Mozilla Firefox, atau Microsoft Edge.
2. Editor kode seperti Visual Studio Code.

### Langkah Menjalankan
1. Klon repositori ini ke komputer lokal Anda.
2. Buka direktori proyek melalui editor kode.
3. Jalankan berkas HTML utama melalui ekstensi Live Server agar halaman dilayani melalui protokol HTTP.
4. Amati hasil render pada peramban dan gunakan Developer Tools untuk menelusuri struktur maupun keluaran konsol.

Menjalankan berkas langsung dari sistem berkas dengan skema `file://` tidak dianjurkan karena sebagian fitur peramban, termasuk pengambilan data melalui jaringan, hanya bekerja pada protokol HTTP.

## Tugas Mandiri

### Halaman Daftar Publikasi Penelitian Dosen

**Skenario**

- Merancang halaman web yang menampilkan daftar publikasi ilmiah para dosen.
- Halaman memuat data publikasi dalam tabel terstruktur, logo instansi, dan deskripsi bidang keahlian.

**Spesifikasi Persyaratan**

1. Gunakan struktur dokumen HTML5 standar yang valid menurut W3C.
2. Buat tabel publikasi kompleks yang menerapkan colspan dan rowspan, lengkap dengan thead, tbody, tfoot, dan atribut scope.
3. Susun deskripsi bidang keahlian menggunakan ordered list di tingkat utama dan unordered list di tingkat dalam.
4. Gunakan figure dan figcaption untuk menyertakan diagram alur metodologi riset.
5. Tuliskan deskripsi riset yang memuat minimal tiga entitas karakter khusus.

**Berkas yang Dikumpulkan**

- `02-tugas-standardisasi-konten.html`

Penamaan berkas wajib mengikuti ketentuan di atas. Berkas dengan penamaan yang tidak sesuai tidak akan diperiksa.

## Ketentuan Pengumpulan

1. Kerjakan tugas pada salinan lokal repositori ini.
2. Pastikan kode berjalan tanpa galat sebelum dikirim.
3. Simpan perubahan dengan pesan commit yang deskriptif.
4. Kirim hasil pekerjaan ke repositori daring sebelum tenggat yang ditetapkan.

```bash
git add .
git commit -m "Selesaikan tugas mandiri modul 2"
git push origin main
```

Riwayat commit menjadi bagian dari penilaian. Kerjakan secara bertahap dan hindari mengunggah seluruh pekerjaan dalam satu commit di akhir.

## Kriteria Penilaian

| Aspek | Bobot |
| --- | --- |
| Ketepatan pemenuhan spesifikasi | 40% |
| Kebenaran dan kerapian penulisan kode | 25% |
| Penerapan standar dan praktik terbaik | 20% |
| Kelengkapan dokumentasi dan riwayat commit | 15% |

## Integritas Akademik

Seluruh pekerjaan harus merupakan hasil karya sendiri. Pemanfaatan referensi dari sumber lain diperkenankan sepanjang dicantumkan sumbernya dan dipahami secara utuh. Penyalinan pekerjaan tanpa atribusi dikenai sanksi sesuai peraturan akademik yang berlaku.

## Lisensi

Materi pada repositori ini digunakan untuk keperluan pembelajaran di lingkungan Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.
