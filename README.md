# Program Autentikasi Sederhana (C++)

Program C++ sederhana berbasis terminal (CLI) untuk simulasi sistem login bertingkat menggunakan struktur kontrol percabangan `if - else if - else`.

---

## 📌 Deskripsi

Program ini menerima input berupa **Nama** dan **Password** dari pengguna, lalu mencocokkannya dengan data statis yang telah ditentukan di dalam kode sumber:

* **Bos**: Username `ronzz` dengan password `ronzz123`.
* **Owner**: Username `rafi` dengan password `rafitzy7`.
* **Akses Ditolak**: Untuk semua kombinasi nama dan sandi selain dua opsi di atas (menampilkan pesan `lu siapa mpruy`).

---

## 🛠️ Logika & Struktur Kode

* `string n, pw`: Menampung string input nama pengguna dan kata sandi.
* `cin >> n` & `cin >> pw`: Membaca input yang diketikkan pengguna.
* Operator logika `&&` (AND): Memastikan username **dan** password harus sama-sama benar agar kondisi bernilai valid.
* Percabangan `if` - `else if` - `else`:
  1. `if`: Mengecek kredensial akun **Bos**.
  2. `else if`: Mengecek kredensial akun **Owner** jika kondisi pertama salah.
  3. `else`: Menampilkan pesan penolakan jika semua kondisi tidak terpenuhi.

---

## 🚀 Cara Menjalankan Program

### 1. Menggunakan Web Compiler (Programiz) — *Paling Mudah*

Kamu bisa langsung menjalankan program ini di browser tanpa perlu menginstal aplikasi apapun:

1. Buka tautan: [Programiz C++ Online Compiler](https://www.programiz.com/cpp-programming/online-compiler/).
2. Hapus seluruh kode bawaan yang ada di editor Programiz.
3. Salin (*copy*) seluruh kode dari file `main.cpp` di repositori ini, lalu tempel (*paste*) ke editor Programiz.
4. Klik tombol biru **Run** di bagian atas.
5. Pada bagian jendela terminal/output di sebelah kanan, ketikkan input nama dan password sesuai prompt yang diminta, lalu tekan **Enter**.

---

By RonzzDev2026

