# Praktikum Struktur Data - Tipe Data, Array, dan Record (C++)

Repository ini berisi beberapa contoh program C++ yang membahas konsep dasar **array**, **record (struct)**, serta **array of record**.  
Program-program ini dibuat untuk memahami cara menyimpan, mengakses, dan mengolah data menggunakan struktur data sederhana.

---

# Daftar Program

## 1. Menampilkan Isi Array
Program ini menampilkan seluruh elemen dari sebuah array menggunakan perulangan `for`.  
Setiap elemen array diakses menggunakan indeks dan ditampilkan ke layar.

---

## 2. Mengakses Array di Luar Batas
Program ini menunjukkan contoh ketika array diakses melebihi batas ukurannya.  
Tujuannya untuk memperlihatkan bahwa akses indeks yang tidak valid dapat menghasilkan data yang tidak terduga.

---

## 3. Input Array dari User
Program ini menerima input beberapa nilai dari pengguna dan menyimpannya ke dalam array.  
Setelah semua data dimasukkan, program akan menampilkan kembali nilai-nilai tersebut.

---

## 4. Menghitung Rata-rata Nilai
Program ini menghitung total dan rata-rata dari beberapa nilai yang dimasukkan oleh pengguna.  
Nilai disimpan dalam array kemudian dijumlahkan untuk memperoleh rata-rata.

---

## 5. Mencari Nilai Maksimum
Program ini digunakan untuk mencari nilai terbesar dari sekumpulan data dalam array.  
Proses pencarian dilakukan dengan membandingkan setiap elemen menggunakan kondisi `if`.

---

## 6. Menentukan Kelulusan Mahasiswa
Program ini menentukan status kelulusan mahasiswa berdasarkan nilai yang dimasukkan.  
Jika nilai ≥ 75 maka mahasiswa dinyatakan **lulus**, sedangkan jika nilai < 75 maka **tidak lulus**.

---

## 7. Array 2 Dimensi (Matriks)
Program ini menampilkan seluruh elemen dari array dua dimensi atau matriks.  
Akses data dilakukan menggunakan **nested loop** (perulangan bersarang) untuk membaca setiap baris dan kolom.

---

## 8. Array of Record Mahasiswa
Program ini menggunakan **struct** untuk menyimpan data mahasiswa yang terdiri dari:
- NPM
- Nama
- Jurusan
- Umur
- Hobi

Data mahasiswa disimpan dalam **array of record**, sehingga program dapat menyimpan beberapa mahasiswa sekaligus.  
Program kemudian akan menginput data tersebut dan menampilkannya kembali ke layar.

---

# Konsep yang Dipelajari

Beberapa konsep dasar struktur data yang digunakan dalam program ini:

- Tipe data dasar pada C++
- Array
- Array satu dimensi
- Array dua dimensi (matrix)
- Struct / Record
- Array of Struct
- Perulangan (`for`)
- Percabangan (`if`)

---

# Bahasa Pemrograman
Program dibuat menggunakan:

- **C++**
- Compiler yang dapat digunakan: `g++`, `Dev-C++`, `CodeBlocks`, atau `VSCode`.

---

# Tujuan
Tujuan dari program-program ini adalah untuk memahami cara:
- menyimpan banyak data dalam array
- mengakses elemen array menggunakan indeks
- menggunakan struct untuk menyimpan data yang lebih kompleks
- menggabungkan array dengan struct (array of record)
