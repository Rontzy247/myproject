# Program Autentikasi Sederhana (C++)

Program C++ sederhana berbasis terminal (CLI) untuk simulasi sistem login bertingkat menggunakan struktur kontrol percabangan `if-else if-else`.

---

## 📌 Deskripsi

Program ini menerima input berupa **Nama** dan **Password** dari pengguna via terminal, lalu mencocokkannya dengan data statis yang telah ditentukan di dalam kode sumber:

* **Bos**: Username `ronzz` dengan password `ronzz123`.
* **Owner**: Username `rafi` dengan password `rafitzy7`.
* **Akses Ditolak**: Untuk semua kombinasi nama dan sandi selain dua opsi di atas.

---

## 🛠️ Logika & Struktur Kode

* `string n, pw`: Menampung string input nama pengguna dan kata sandi.
* `cin >> n` & `cin >> pw`: Membaca masukan dari pengguna secara sekuensial.
* Operator logika `&&` (AND): Memastikan kecocokan nama **dan** sandi sekaligus sebelum mengeksekusi blok pesan selamat datang.
* Percabangan `if` - `else if` - `else`:
  1. Mengecek kredensial akun **Bos**.
  2. Mengecek kredensial akun **Owner** jika kondisi pertama tidak terpenuhi.
  3. Menampilkan pesan penolakan jika seluruh kondisi sebelumnya salah.

---

## 💻 Cara Menjalankan

### 1. Menggunakan Compiler Lokal (g++)

Jalankan perintah berikut di terminal:

```bash
# Compile program
g++ main.cpp -o program_login

# Jalankan file binary (Linux/macOS)
./program_login

# Atau jalankan di Windows
program_login.exe
