🚀 NextAdmin - Admin Panel & Form Builder Modern

NextAdmin adalah Admin Panel dan Form Builder Modern yang dirancang untuk memudahkan pembuatan dashboard dan pengelolaan database secara otomatis.
Dibangun dengan Next.js 14, React, Express.js, Prisma ORM, dan teknologi modern lainnya.

✨ Fitur Utama
Form Builder Dinamis → Buat formulir kompleks dengan mudah tanpa coding manual.
Auto Database Generation → Generate database dan model otomatis dari form builder.
Backend Cepat & Ringan → Menggunakan Express.js sebagai API server.
Authentication & Authorization → Menggunakan NextAuth.js untuk autentikasi.
Component UI Modular → Menggunakan React & Tailwind CSS untuk tampilan responsif.
Mode Gelap & Responsif → UI modern dengan tema yang bisa disesuaikan.
🚀 Teknologi yang Digunakan
Next.js 14 - SSR & Frontend Framework
React - Component-based UI
Express.js - Backend API
Prisma ORM - Database Management
Tailwind CSS - Styling
Zod - Schema Validation
NextAuth.js - Authentication
TypeScript - Typed JavaScript
📦 Instalasi & Menjalankan Proyek
Pastikan Anda telah menginstal Node.js versi terbaru dan npm atau yarn.

1️⃣ Clone Repository
```sh
git clone https://github.com/username/repo-name.git
cd repo-name
```
2️⃣ Install Dependencies
```sh
npm install
# atau
yarn install
```
3️⃣ Setup Environment Variables
Buat file .env dan tambahkan konfigurasi berikut:

```sh
DATABASE_URL="postgresql://user:password@localhost:5432/database"
NEXTAUTH_SECRET="your-secret-key"
```
4️⃣ Jalankan Prisma Migration
```sh
npx prisma migrate dev
```
5️⃣ Jalankan Server
```sh
npm run dev
```
6️⃣ Akses di Browser
Buka http://localhost:3000

🎯 Struktur Proyek
```bash
/src
  ├── components    # Reusable React components
  ├── pages         # Next.js Pages
  ├── server        # Express API
  ├── prisma        # Prisma ORM setup
  ├── styles        # Tailwind CSS & global styles
  ├── utils         # Helper functions
```
🛠️ Kontribusi
Kami sangat terbuka dengan kontribusi dari komunitas! Ikuti langkah berikut:

🔹 Cara Berkontribusi
Fork repository ini
Buat branch baru untuk fitur Anda
```sh
git checkout -b fitur-baru
```

Commit perubahan Anda
```sh
git commit -m "Menambahkan fitur X"
```
Push branch ke GitHub
```sh
git push origin fitur-baru
```

Buka Pull Request (PR) dan tunggu review dari tim.
🔹 Aturan Kontribusi
Gunakan TypeScript untuk semua kode baru.
Ikuti konvensi coding yang konsisten dengan proyek ini.
Pastikan kode Anda bebas dari error atau warning.
Tambahkan dokumentasi untuk fitur baru.
📄 Lisensi
Proyek ini dirilis di bawah MIT License.
Silakan gunakan, modifikasi, dan kembangkan sesuai kebutuhan.

🔥 Jangan lupa beri ⭐ di repository ini jika proyek ini bermanfaat!
