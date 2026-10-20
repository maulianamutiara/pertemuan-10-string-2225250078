# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Mauliana Mutiara  
**NIM:** 2225250078  
**Kelas:** 3A

## Tujuan

Tujuan praktikum ini adalah mempelajari cara mengolah teks menggunakan string pada Python. Saya belajar menggunakan fungsi string untuk merapikan teks, mengubah huruf, memisahkan kata, dan menggabungkan kata. Materi ini juga diterapkan pada tugas normalisasi data mahasiswa.

## Cara Menjalankan

Program dijalankan melalui terminal di VS Code. Pastikan terminal berada di folder utama repository, kemudian ketik perintah berikut:

```bash
python tugas/normalisasi_data_mahasiswa.py
```

Setelah program dijalankan, masukkan nama dan kode kelas sesuai petunjuk yang muncul di terminal.

## Algoritma

Pertama, program meminta pengguna memasukkan nama dan kode kelas. Nama dirapikan dengan menghilangkan spasi berlebih, kemudian diubah agar setiap kata diawali huruf kapital. Kode kelas diubah menjadi huruf besar dan spasi antarbagian diganti dengan tanda hubung.

Selanjutnya, program menghitung jumlah kata pada nama dan mengambil huruf pertama setiap kata untuk dijadikan inisial. Setelah semua proses selesai, program menampilkan nama bersih, kode kelas, jumlah kata, dan inisial.

## Test Case

| No. | Input Nama | Input Kode Kelas | Hasil yang Diharapkan |
|---|---|---|---|
| 1 | aan hendrayana | pmat a 2026 | Aan Hendrayana, PMAT-A-2026, 2 kata, AH |
| 2 | fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah, KELAS-B, 2 kata, FM |
| 3 | BUDI | pmtk 01 | Budi, PMTK-01, 1 kata, B |
| 4 | siti nur aisyah | kelas c | Siti Nur Aisyah, KELAS-C, 3 kata, SNA |

**Hasil aktual:** Diisi berdasarkan hasil yang muncul di terminal setelah setiap test case dijalankan.


## Refleksi

Dari praktikum ini, saya lebih memahami penggunaan fungsi string untuk mengolah teks. Saya belajar bahwa setiap fungsi memiliki kegunaan yang berbeda, seperti `strip()` untuk membersihkan spasi di awal dan akhir, `title()` untuk mengubah kapitalisasi nama, serta `split()` dan `join()` untuk memisahkan dan menggabungkan kata.

Saya juga belajar untuk lebih teliti saat menulis kode. Jika program belum menghasilkan keluaran yang sesuai, saya perlu memeriksa kode dan mencoba menjalankannya kembali.


