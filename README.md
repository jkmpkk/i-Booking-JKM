# i-Booking JKM

**Sistem Tempahan Peralatan Jabatan Kejuruteraan Mekanikal**  
Politeknik Kota Kinabalu

Satu fail HTML ringkas dan mesra pengguna untuk menguruskan tempahan **Projector** dan **Laptop** oleh staf JKM.

---

## ✨ Ciri-ciri Utama

- **Dua Jenis Peralatan**: Projector & Laptop
- **Jadual Keseluruhan** yang berasingan untuk setiap jenis peralatan
- **Paparan mengikut Pemegang** (En. Ahmad, Pn. Siti, En. Lee, Pn. Fatimah, dll.)
- **Tempahan Biasa** atau **Tempahan Semester** (berulang)
- **Admin Panel** untuk menguruskan:
  - Senarai peminjam
  - Senarai pemegang peralatan
  - Sesi semasa
  - Padam semua booking
- Data disimpan secara **localStorage** (kekal walaupun refresh)
- Responsive & mesra mobile
- Font **Roboto** yang moden

---

## 🚀 Cara Menggunakan

1. Buka fail `i-Booking-JKM-updated.html` menggunakan mana-mana browser moden (Chrome, Edge, Firefox, dll.).
2. Klik butang besar:
   - **📽️ Pinjam Projector**
   - **💻 Pinjam Laptop**
3. Pilih **Pemegang** yang dikehendaki → jadual mengikut pemegang akan dipaparkan.
4. Klik sel kosong pada jadual untuk buat tempahan baru.
5. Isi borang tempahan (Nama Peminjam, Tarikh, Masa, Jenis Tempahan).
6. Klik **Hantar Booking**.

Untuk melihat **Jadual Keseluruhan**, klik butang **← Kembali ke Jadual Keseluruhan** di bahagian atas.

---

## 🔐 Admin Panel

Untuk masuk ke Admin Panel:

1. Klik ikon **gear** (⚙️) di bahagian kanan atas.
2. Masukkan kata laluan: **`jkm123`**
3. Admin Panel akan muncul.

### Fungsi Admin:
- **Tambah / Padam Nama Peminjam**
- **Tambah / Padam Pemegang Peralatan** (Projector & Laptop)
- **Kemaskini Sesi Semasa** (contoh: Sesi 2025/2026)
- **Upload Excel/CSV** untuk tambah ramai peminjam sekaligus
- **Padam Semua Booking** (reset)

> **Nota**: Pemegang default (En. Ahmad, Pn. Siti, En. Lee, Pn. Fatimah) hanya ditambah sekali pada kali pertama. Anda boleh padamnya jika mahu.

---

## 🛠️ Teknologi Digunakan

| Teknologi              | Kegunaan                          |
|------------------------|-----------------------------------|
| HTML5 + Tailwind CSS   | Antara muka moden & responsive    |
| Vanilla JavaScript     | Logik keseluruhan aplikasi        |
| Lucide Icons           | Ikon-ikon cantik                  |
| XLSX.js                | Import data dari Excel/CSV        |
| localStorage           | Penyimpanan data (tiada backend)  |

---

## 📁 Struktur Fail

Projek ini adalah **single-file application**:

```
i-Booking-JKM-updated.html   ← Fail utama (semua kod di sini)
README.md                    ← Dokumentasi ini
```

Tiada fail lain diperlukan. Cukup buka fail HTML sahaja.

---

## ⚠️ Nota Penting

- Data disimpan di **browser localStorage**. Jika anda buka fail di komputer lain atau clear browser data, data akan hilang.
- Untuk kegunaan sebenar di makmal komputer, disyorkan simpan fail di satu komputer yang sama.
- Tailwind CSS menggunakan Play CDN (sesuai untuk prototaip & kegunaan dalaman).
- Tidak memerlukan sebarang pemasangan atau server.

---

## 📌 Cadangan Penambahbaikan Masa Depan

- Integrasi dengan Google Sheet / Firebase (backend sebenar)
- Sistem notifikasi email
- QR Code untuk check-in peralatan
- Laporan & statistik tempahan
- Tema gelap / warna institusi

---

## 👨‍🏫 Kredit

Dibangunkan untuk **Jabatan Kejuruteraan Mekanikal (JKM)**  
Politeknik Kota Kinabalu  
© 2026

---

**Selamat menggunakan!**  
Sebarang soalan atau cadangan, sila hubungi pentadbir sistem di ijkmpkk@gmail.com.
