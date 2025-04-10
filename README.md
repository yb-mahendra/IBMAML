# README

# 🚖 Driver Management System - Final Project Python

Project ini merupakan tugas akhir sederhana yang dibuat menggunakan **Python**. Program ini menyediakan fitur manajemen data driver taksi dengan sistem **CRUD (Create, Read, Update, Delete)** yang interaktif berbasis console.

## 📌 Deskripsi

Aplikasi ini dirancang untuk membantu operator dalam mencatat, memfilter, dan memodifikasi data driver serta kendaraan armada taksi berdasarkan wilayah **Surabaya Raya** (Surabaya, Sidoarjo/Gresik, Mojokerto/Lamongan).

Setiap driver memiliki data sebagai berikut:
- Nomor urut
- Nama driver
- TNKB (Tanda Nomor Kendaraan Bermotor) otomatis dan unik
- Jenis kendaraan (Sedan, MPV, SUV, dll.)
- Jenis taksi (Reguler, Premium, Elektrik)
- Nomor HP
- Alamat

---

## ⚙️ Fitur Program

✅ Menampilkan daftar driver dalam bentuk tabel  
✅ Filter driver berdasarkan **jenis kendaraan**  
✅ Filter driver berdasarkan **jenis taksi**  
✅ Tambah driver baru dengan **TNKB unik otomatis** sesuai wilayah  
✅ Edit data driver berdasarkan **nomor urut**  
✅ Hapus data driver dari sistem 
✅ Upgrade jenis taksi driver (assign dari Reguler ke Premium atau Elektrik)
✅ Interaktif berbasis input console  


## 🏙 TNKB Generation

TNKB (plat nomor) akan di-generate otomatis berdasarkan kota asal dari alamat:

- `L` = Surabaya
- `W` = Sidoarjo / Gresik
- `S` = Mojokerto / Lamongan

Contoh format: `L 1234 AB`

## ▶️ How to Run

1. Clone repo ini atau salin `driver_management.py`
2. Jalankan di terminal atau IDE:

```bash
python driver_management.py

---
=== Selamat Datang di Driver Management System ===
1. Tampilkan Daftar Driver
2. Filter Jenis Kendaraan
3. Filter Jenis Taksi
4. Tambah Data Driver
5. Edit Data Driver
6. Hapus Data Driver
7. Assign Driver (Upgrade)
8. Exit

