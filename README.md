# 🏨 hotelreservation-python

Program Manajemen Reservasi Hotel Berbasis Python (CLI) — Lengkap dengan Pemesanan Kamar, Tagihan, dan Pembayaran.

---

## 📌 Fitur Utama

✅ Pemesanan kamar dengan beberapa tipe:
- Standard Single Bed
- Standard Twin Beds
- Superior Queen Bed
- Deluxe Room

✅ Input data pelanggan: nama, nomor HP, tanggal check-in/check-out  
✅ Pemesanan menu sarapan: makanan berat, makanan ringan, minuman  
✅ Perhitungan total tagihan otomatis  
✅ Pilihan metode pembayaran: transfer bank, virtual account, e-wallet, atau cash  
✅ Diskon 5% otomatis untuk pembayaran dengan virtual account/e-wallet  
✅ Login admin untuk melihat data pelanggan  
✅ Informasi detail fasilitas dan harga kamar

---

## 🚀 Cara Menjalankan

1. Pastikan Python 3.x sudah terinstal di komputer.
2. Clone repository ini:
    ```bash
    git clone https://github.com/rizdhandevcode/hotelreservation-python.git
    cd hotelreservation-python
    ```
3. Jalankan program:
    ```bash
    python main.py
    ```

---

## 🔑 Akun Admin

- **Username:** admin  
- **Password:** admin  

Digunakan untuk login admin agar dapat melihat data pelanggan.

---

## 📚 Dependensi

- [pandas](https://pandas.pydata.org/) — untuk menampilkan data pelanggan dalam bentuk tabel.
- [getpass](https://docs.python.org/3/library/getpass.html) — modul bawaan Python untuk input password admin secara aman.

Install dependensi dengan:
```bash
pip install pandas
