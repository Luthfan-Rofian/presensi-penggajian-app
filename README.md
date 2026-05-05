# 🧑‍💼 Sistem Presensi & Penggajian Karyawan (HRIS)  
## Ponpes Darul Ulum Tlasih

Sistem Presensi dan Penggajian berbasis web (HRIS) yang dirancang untuk mengelola kehadiran, data karyawan, serta proses penggajian secara otomatis dan terintegrasi.

🚧 **Status: Development Project**

---

## 📌 Tentang Proyek

Aplikasi ini merupakan bagian dari digitalisasi sistem internal Pondok Pesantren Darul Ulum Tlasih yang berfokus pada pengelolaan sumber daya manusia (SDM).

Sistem ini digunakan untuk:
- Monitoring kehadiran karyawan
- Validasi aktivitas kerja
- Otomatisasi penggajian
- Pengelolaan data pegawai secara terpusat

⚠️ **Catatan:**  
Sistem ini **khusus untuk karyawan/pegawai**, bukan untuk santri.

Digunakan oleh:
- Staff administrasi  
- Ustadz / tenaga pengajar  
- Karyawan operasional  

---

## 🎯 Tujuan Pengembangan

- Mengurangi sistem absensi manual
- Meningkatkan akurasi data kehadiran
- Mempermudah proses payroll
- Meningkatkan transparansi data SDM
- Mendukung transformasi digital pesantren

---

## ✨ Fitur Utama

- 📍 **Absensi Berbasis Lokasi (GPS / Geofencing)**  
- 🤳 **Validasi Selfie (Anti Titip Absen)**  
- ✅ **Approval Presensi (Admin / Atasan)**  
- 💰 **Perhitungan Gaji Otomatis (Payroll)**  
- 📊 **Dashboard Monitoring Karyawan**  
- 📱 **Mobile Friendly / PWA Ready**  

💡 Sistem presensi modern umumnya menggunakan GPS dan validasi foto untuk memastikan keakuratan data kehadiran. :contentReference[oaicite:0]{index=0}  

---

## 🛠️ Tech Stack

- **Framework**: Laravel  
- **Bahasa Pemrograman**: PHP 8+  
- **Database**: MySQL  
- **Frontend**: Blade / Tailwind CSS  
- **Arsitektur**: MVC  

---

## 🏗️ Arsitektur Sistem

```
Karyawan
   ↓
Presensi (GPS + Selfie)
   ↓
Database
   ↓
Validasi Admin
   ↓
Payroll Processing
   ↓
Dashboard & Laporan
```

---

## ⚙️ Instalasi

```bash
git clone https://github.com/Luthfan-Rofian/presensi-penggajian-app.git
cd presensi-penggajian-app

composer install
npm install

cp .env.example .env
php artisan key:generate
```

### 🔧 Konfigurasi Database

Edit file `.env`:

```
DB_DATABASE=your_database
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### ▶️ Jalankan Aplikasi

```bash
php artisan migrate
php artisan serve
```

Akses di:  
http://localhost:8000

---

## 🔗 Integrasi Sistem Pesantren

Sistem ini merupakan bagian dari ekosistem digital:

| Sistem | Fungsi |
|------|--------|
| 🌐 Web Profile | Informasi publik |
| 🧾 PSB | Pendaftaran santri |
| 🧑‍💼 HRIS | Manajemen karyawan (project ini) |

---

## 🚀 Roadmap Pengembangan

- [ ] Notifikasi WhatsApp / Email  
- [ ] Export laporan (PDF / Excel)  
- [ ] Integrasi fingerprint / RFID  
- [ ] Multi-role (Admin, HRD, Manager)  
- [ ] Sistem cuti & izin  
- [ ] Slip gaji otomatis  
- [ ] API integrasi sistem lain  

---

## 📊 Use Case

Sistem ini dapat digunakan untuk:
- Pondok Pesantren  
- Sekolah / Kampus  
- Perusahaan  
- Organisasi  

---

## 💸 Dukungan Pengembangan

Jika Anda ingin mendukung pengembangan sistem ini:

👉 **Dukung di Saweria**  
https://saweria.co/Luthfanrofian

---

## ❤️ Kontribusi

Kontribusi terbuka untuk pengembangan lebih lanjut:

1. Fork repository  
2. Buat branch fitur  
3. Commit perubahan  
4. Ajukan pull request  

---

## 📄 Lisensi

Silakan sesuaikan dengan lisensi yang digunakan pada repository ini.

---

## 👨‍💻 Pengembang

Dikembangkan oleh:

**DigitalNote by Rofian**

---

<p align="center">
🚀 Menuju Sistem ERP Pesantren Terintegrasi
</p>
