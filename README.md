# 🍕 Program Sistem Pemesanan Pizza

### Algoritma Pemrograman - Sistem Pemesanan Pizza

Ini adalah proyek pemrograman interaktif yang dibuat sebagai bagian dari tugas Algoritma dan Pemrograman. Program ini memungkinkan pengguna untuk memilih pizza, jenis crust, ukuran pizza, dan tambahan keju, kemudian menampilkan ringkasan pesanan lengkap beserta total tagihan.

## 📋 Fitur Utama
- **Input Pengguna**: Pengguna memasukkan nama dan memilih pizza dari menu yang disediakan.
- **Pilihan Variatif**: Tersedia berbagai pilihan jenis pizza, crust, dan ukuran.
- **Opsi Tambahan Keju**: Pengguna bisa memilih untuk menambahkan keju dengan biaya tambahan.
- **Ringkasan Pesanan**: Setelah semua pilihan dibuat, program akan menampilkan ringkasan pesanan serta total harga.

## 📊 Flowchart
Kamu bisa melihat alur kerja program dalam bentuk flowchart yang tersedia di tautan berikut:
[Flowchart Program](https://github.com/Fawrz/Program-Sistem-Pemesanan-Pizza-/blob/main/Flowchart.jpg)

Berikut alur kerja utama program berdasarkan flowchart:
1. **Mulai**: Program memulai dengan pesan sambutan "Welcome to AENS Pizza".
2. **Input Nama**: Pengguna diminta untuk memasukkan nama mereka.
3. **Pilih Pizza**: Pengguna memilih pizza dari daftar menu yang disajikan.
4. **Pilih Crust**: Pengguna memilih jenis crust yang diinginkan.
5. **Pilih Ukuran Pizza**: Pengguna memilih ukuran pizza.
6. **Tambahan Keju**: Pengguna dapat menambahkan keju dengan biaya ekstra.
7. **Ringkasan Pesanan**: Program menampilkan detail pesanan termasuk nama pengguna, jenis pizza, crust, ukuran, dan tambahan keju (jika dipilih).
8. **Konfirmasi Pesanan**: Pengguna mengonfirmasi pesanan yang telah dibuat.
9. **Selesai**: Setelah konfirmasi, program menampilkan pesan terima kasih dan menyelesaikan proses pemesanan.

## 🖥️ Source Code
Program ini ditulis menggunakan bahasa **Python** dan memanfaatkan struktur logika seperti `while loops` serta `if-else statements` untuk menangani input pengguna dan validasi.

Kamu bisa melihat atau mengunduh source code lengkap di tautan berikut:
[Source Code Program](https://github.com/Fawrz/Program-Sistem-Pemesanan-Pizza-/blob/main/main.py)

### Contoh Kode:
```python
print("-------------------- WELCOME TO AENS PIZZA --------------------\n")
name = input("Please enter your name: ")
print("""List Menu Pizza:
1. Frankfurter BBQ - Rp 85.000
2. Meat Monster - Rp 110.000
3. Super Supreme - Rp 100.000
...
""")
choice_pizza = input("Choose your pizza by number: ")
if choice_pizza == "1":
    total_bill += 85000
    pizza_name = "Frankfurter BBQ (Rp 85.000)"
