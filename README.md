# Pertemuan 10 - String dan Pengolahan Teks Python

**Nama:** Sela Widiyanti
**NIM:** 2225250176  
**Kelas:** 3F

## Tujuan

Praktik ini bertujuan memahami penggunaan string dalam Python, mulai dari mengakses karakter, mengambil sebagian teks, mengubah huruf, membersihkan spasi, memisahkan dan menggabungkan kata, hingga melakukan pencarian dan normalisasi data teks.

## Struktur Program

- `latihan/01_dasar_string.py`: mengenal string, panjang teks, huruf besar dan huruf kecil.
- `latihan/02_indeks_slicing.py`: mengakses karakter, slicing, dan membalik teks.
- `latihan/03_method_string.py`: menggunakan strip(), title(), dan upper().
- `latihan/04_bersihkan_teks.py`: membersihkan spasi berlebih.
- `latihan/05_split_join.py`: memisahkan dan menggabungkan kata.
- `latihan/06_pencarian_kata.py`: mencari dan menghitung kemunculan kata.
- `tugas/normalisasi_data_mahasiswa.py`: membersihkan nama, menyeragamkan kode kelas, menghitung jumlah kata, dan membuat inisial.

## Cara Menjalankan

Buka folder proyek melalui VS Code, kemudian pilih Terminal → New Terminal. Jalankan setiap program menggunakan perintah berikut.

```bash
python latihan/01_dasar_string.py
python latihan/02_indeks_slicing.py
python latihan/03_method_string.py
python latihan/04_bersihkan_teks.py
python latihan/05_split_join.py
python latihan/06_pencarian_kata.py
python tugas/normalisasi_data_mahasiswa.py
```

## Algoritma Tugas Utama

1. Membaca nama mahasiswa dan kode kelas.
2. Menghapus spasi berlebih pada nama dan mengubahnya menjadi format title case.
3. Memecah nama menjadi kata menggunakan split().
4. Membuat inisial dari huruf pertama setiap kata.
5. Mengubah kode kelas menjadi huruf kapital dan mengganti spasi dengan tanda hubung.
6. Menghitung jumlah kata pada nama.
7. Menampilkan nama bersih, kode kelas, jumlah kata, dan inisial.

## Test Case

| No. | Input nama | Input kode | Hasil yang diharapkan |
|---|---|---|---|
| 1 | aan hendrayana | pmat a 2026 | Aan Hendrayana; PMAT-A-2026; 2 kata; AH |
| 2 | fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah; KELAS-B; 2 kata; FM |
| 3 | BUDI | pmtk 01 | Budi; PMTK-01; 1 kata; B |
| 4 | siti nur aisyah | kelas c | Siti Nur Aisyah; KELAS-C; 3 kata; SNA |

Catat hasil aktual dan status setiap pengujian setelah program dijalankan.

| No. | Hasil aktual | Status |
|---|---|---|
| 1 | [Isi hasil pengujian] | [Lulus/Perlu perbaikan] |
| 2 | [Isi hasil pengujian] | [Lulus/Perlu perbaikan] |
| 3 | [Isi hasil pengujian] | [Lulus/Perlu perbaikan] |
| 4 | [Isi hasil pengujian] | [Lulus/Perlu perbaikan] |

## Refleksi

Dari praktik ini, saya memahami bahwa string digunakan untuk mengolah data berbentuk teks. Method seperti strip(), upper(), lower(), split(), dan join() membantu membersihkan serta menyeragamkan teks. Saya juga mempelajari bahwa string bersifat immutable, sehingga perubahan teks dilakukan dengan menghasilkan string baru.

**Kendala yang saya temukan:** [Tuliskan kendala yang benar-benar dialami dan cara memperbaikinya.]

## Referensi

- Bahan Ajar Algoritma dan Pemrograman, Pertemuan 10: String dan Pengolahan Teks.
- Python 3 Documentation, Text Sequence Type — str.
