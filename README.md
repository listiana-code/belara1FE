# Belara1 Frontend (React)

Ini adalah bagian frontend dari aplikasi Belara1, yang dikembangkan menggunakan React.js. Frontend ini terintegrasi dengan backend Laravel yang berada di repositori terpisah.

## 🚀 Fitur

- Dibangun dengan React.js
- Struktur proyek modern dan modular
- Integrasi API ke backend Laravel
- Manajemen state dan komponen yang terstruktur
- Mendukung styling menggunakan CSS/SCSS/Library (tergantung implementasi)

## 📦 Prasyarat

Pastikan Anda sudah menginstal:

- Node.js >= 16.x
- npm atau yarn
- Backend Laravel (lihat [Belara1 Backend](#) untuk setup backend)

## 🛠️ Instalasi

1. **Clone repository ini**
   ```bash
   git clone https://github.com/username/fereact.git
   cd fereact
   ```

2. **Install dependensi**
   ```bash
   npm install
   ```
   atau jika menggunakan Yarn:
   ```bash
   yarn install
   ```

3. **Konfigurasi koneksi ke backend (jika diperlukan)**
   
   Buka file konfigurasi (misalnya `.env`, `api.js`, atau sesuai struktur proyek), dan sesuaikan URL API backend:

   ```
   REACT_APP_API_URL=http://localhost:8000/api
   ```

4. **Jalankan aplikasi**
   ```bash
   npm start
   ```
   Aplikasi akan berjalan di `http://localhost:3000`

## 📁 Struktur Proyek

- `src/` — Berisi semua source code React
  - `components/` — Komponen UI
  - `pages/` — Halaman utama
  - `services/` — Koneksi API dan logic lainnya
  - `App.js` — Entry point utama
- `public/` — File statis
- `.env` — Konfigurasi variabel environment (opsional)

## 🧪 Testing (Jika Ada)

Jika tersedia testing, jalankan dengan:

```bash
npm test
```

## 🔗 Integrasi Backend

Frontend ini dibuat untuk berkomunikasi langsung dengan Laravel backend melalui REST API. Pastikan backend Laravel sudah aktif dan endpoint API sesuai dengan konfigurasi di frontend.

## 📄 Lisensi

Proyek ini menggunakan lisensi [MIT](LICENSE).

---

> Dibuat dengan ❤️ menggunakan React.js dan Laravel.
