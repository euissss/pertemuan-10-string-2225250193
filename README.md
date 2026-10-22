
# Pertemuan 10 - String dan Pengolahan Teks

Nama: Euis Hasanah Ramadani
NIM: 2225250193
Kelas: 3F

## Tujuan
Mengolah dan menormalisasi data teks menggunakan string Python, termasuk membersihkan spasi, menyeragamkan kapitalisasi, memisahkan kata, dan membentuk inisial mahasiswa.

## Struktur Program
- `latihan/01_dasar_string.py`: Operasi dasar string.
- `latihan/02_indeks_slicing.py`: Mengakses karakter dan melakukan slicing.
- `latihan/03_method_string.py`: Menggunakan method string.
- `latihan/04_bersihkan_teks.py`: Membersihkan spasi berlebih.
- `latihan/05_split_join.py`: Memisahkan dan menggabungkan kata.
- `latihan/06_pencarian_kata.py`: Mencari dan menghitung kemunculan kata.
- `tugas/normalisasi_data_mahasiswa.py`: Normalisasi nama dan kode kelas.

## Cara Menjalankan
Jalankan perintah berikut dari folder utama proyek:

python3 tugas/normalisasi_data_mahasiswa.py

## Algoritma
Program menerima nama mahasiswa dan kode kelas. Nama dibersihkan menggunakan strip dan split, kemudian diseragamkan menggunakan title. Kode kelas diubah menjadi huruf besar, dipecah menjadi beberapa bagian, lalu digabungkan menggunakan tanda hubung. Program juga menghitung jumlah kata dan membentuk inisial dari setiap kata nama.

## Test Case
1. Nama: aan hendrayana
   Kode: pmat a 2026
   Hasil: Aan Hendrayana, PMAT-A-2026, AH

2. Nama: fATHIYYAH mUTHMAINNAH
   Kode: kelas b
   Hasil: Fathiyyah Muthmainnah, KELAS-B, FM

3. Nama: BUDI
   Kode: pmtk 01
   Hasil: Budi, PMTK-01, B

4. Nama: siti nur aisyah
   Kode: kelas c
   Hasil: Siti Nur Aisyah, KELAS-C, SNA

## Refleksi
Saya memahami bahwa string merupakan urutan karakter yang bersifat immutable. Method seperti strip, title, upper, split, dan join dapat digunakan untuk membersihkan serta menyeragamkan data teks. Saya juga memahami bahwa fungsi membuat proses pengolahan teks lebih terstruktur dan dapat digunakan kembali.
