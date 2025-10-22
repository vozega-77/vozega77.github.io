# 🌿 AsalUsul for Cultural Heritage by Zega Brothers

![Status](https://img.shields.io/badge/status-prototype-green)
![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-blue?logo=tailwindcss)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript)
![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)
![Made with ❤️](https://img.shields.io/badge/Made%20with-%F0%9F%92%9E%20by%20AsalUsul%20Team-pink)

> “Setiap Karya Punya Cerita. Setiap Cerita Punya Nilai.”  
> — *AsalUsul for Cultural Heritage*

---

## 📖 Deskripsi Singkat

**AsalUsul** adalah prototipe aplikasi web untuk *Paspor Digital Produk* — sebuah inovasi yang menghadirkan transparansi dan keaslian bagi produk budaya, kerajinan, dan karya tangan lokal.  
Melalui satu pemindaian QR Code, pengguna dapat melihat perjalanan produk, profil pembuatnya, hingga kisah yang menginspirasi di baliknya.

---

## 🚀 Fitur Utama

### 🏠 Landing Page
Menampilkan konsep utama “Paspor Digital Produk dengan Satu Pindai” dan tiga langkah sederhana:
1. **Daftarkan & Cetak** – Kreator mendaftarkan produk dan menerima QR Code unik.
2. **Pindai & Lacak** – Pihak logistik mencatat perjalanan produk melalui pemindaian.
3. **Verifikasi & Nikmati** – Konsumen memindai untuk melihat paspor digital produk.

---buatlah dokumentasi untuk website ini untuk saya upload di github project

### 📊 Dashboard Kreator
- Form pendaftaran produk dengan kolom nama, material, pengrajin, dan media (foto/video).
- Fitur **✨ Buat Cerita (AI)** menggunakan **Google Gemini API** untuk menghasilkan deskripsi otomatis.
- Grafik penjualan interaktif menggunakan **Chart.js**.
- Daftar produk lengkap dengan status dan stok.

---

### 🚚 Mode Logistik
- Simulasi pemindaian QR Code.
- Dapat memperbarui status perjalanan produk (*Diterima di Gudang*, *Dalam Pengiriman*, *Tiba di Toko*).
- Data langsung muncul di bagian *Paspor Digital* halaman utama.

---

### 👤 Dashboard Konsumen
- Login sederhana untuk pengguna.
- Menampilkan **profil konsumen** dan **riwayat transaksi**.
- Mode **Pindai Produk** untuk melihat paspor digital secara langsung.

---

## 🧠 Teknologi yang Digunakan

| Teknologi | Deskripsi |
|------------|------------|
| **HTML5** | Struktur halaman utama aplikasi |
| **Tailwind CSS** | Framework CSS utility-first untuk tampilan modern dan responsif |
| **JavaScript (Vanilla)** | Logika interaktif dan navigasi antar halaman |
| **Chart.js** | Menampilkan grafik data penjualan |
| **Gemini API (Google)** | Membuat deskripsi produk otomatis berbasis AI |
| **IPFS & Polygon (Simulasi)** | Representasi sistem penyimpanan dan blockchain desentralisasi |

---

## 🧩 Struktur Folder

```
asalusul-app/
│
├── index.html           # Halaman utama (semua logika dan tampilan di sini)
├── README.md            # Dokumentasi proyek (file ini)
└── assets/              # Folder opsional untuk media tambahan
```

---

## ⚙️ Cara Menjalankan Proyek

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/username/asalusul-app.git
   cd asalusul-app
   ```

2. **Jalankan di browser:**
   ```bash
   open index.html
   ```
   atau cukup klik dua kali pada file `index.html`.

3. **(Opsional) Jalankan server lokal:**
   Untuk mengaktifkan fitur AI atau API lain, jalankan:
   ```bash
   npx serve
   ```
   Lalu buka di browser: `http://localhost:3000`

---

## 🪄 Integrasi AI (Gemini)

Fitur **“✨ Buat Cerita (AI)”** membantu kreator membuat deskripsi produk otomatis.

### Langkah Aktivasi:
1. Dapatkan API Key dari [Google AI Studio](https://makersuite.google.com/app/apikey).  
2. Masukkan API key ke variabel berikut di dalam `index.html`:
   ```js
   const apiKey = "YOUR_API_KEY_HERE";
   ```
3. Klik tombol “✨ Buat Cerita (AI)” pada form pendaftaran produk.

---

## 📸 Preview Tampilan

> 📍 *Gambar di bawah hanya placeholder. Ganti dengan tangkapan layar proyekmu sebelum diunggah.*

| Halaman | Preview |
|----------|----------|
| **Landing Page** | ![Landing Page](https://placehold.co/800x400/f0fdf4/333?text=Landing+Page+Preview) |
| **Dashboard Kreator** | ![Dashboard Kreator](https://placehold.co/800x400/e0f2fe/333?text=Dashboard+Kreator+Preview) |
| **Dashboard Konsumen** | ![Dashboard Konsumen](https://placehold.co/800x400/dcfce7/333?text=Dashboard+Konsumen+Preview) |
| **Mode Logistik (Scan)** | ![Logistics Scan](https://placehold.co/800x400/f1f5f9/333?text=Logistics+Scan+Preview) |

---

## 💡 Konsep Utama

AsalUsul dikembangkan untuk:
- Menjaga **transparansi rantai pasok** (supply chain transparency).
- Membangun **kepercayaan konsumen** terhadap produk lokal.
- Menyediakan **cerita autentik dan bernilai budaya** di balik setiap karya.

---

## 🧑‍💻 Kontributor

| Nama | Peran |
|------|--------|
| **ion ze** | Pengembang & Penulis Dokumentasi |
| **AsalUsul Team** | Desain UI/UX & Konsep Aplikasi |
| **Google Gemini API** | AI Storytelling Integration |

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License** — bebas digunakan dan dimodifikasi dengan mencantumkan atribusi.

---

### 💬 “Made with ❤️ using Tailwind, JavaScript, and creativity.”
