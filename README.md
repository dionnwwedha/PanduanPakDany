# Panduan pembangunan WebGIS dengan NextJS dan Maplibre

## 1. Persiapan dan Instalasi

*Pengantar: Git Version Control*

### *Instalasi*

- Instalasi WSL pada Windows
- Instalasi Npm dan NodeJS
- Instalasi Docker dan Docker Compose
- Instalasi perangkat pendukung (VSCode)
- Beberapa ekstensi yang berguna
- *Trivia: Github Codespaces*

### *Git dan Github*

- Prinsip Git dan Github
- Membuat Akun dan Mengatur Repository
- Commit dan Push
- Prinsip Kolaborasi dengan Github
- *Trivia: Github Copilot*

## 2. Membangun Web dengan NextJS dan TailwindCSS

*Pengantar: Framework dan Library Javascript*

### *Membuat Halaman Web dengan NextJS*

- Sekelumit tentang ReactJS
- Memulai Proyek Create Next App
- Struktur Proyek NextJS
- Navigasi Halaman (Pages)
- Membangun Komponen NextJS
- Komunikasi Antar Komponen dengan Props
- *Trivia: ContextAPI*

### *Membangun Layout Halaman dengan TailwindCSS*

- Instalasi dan Pengaturan TailwindCSS
- Membuat Desain Layout
- Membuat Layout dengan Flex dan Grid
- Melengkapi Komponen Layout
- Deployment ke Github dan Vercel

## 3. WebGIS pada NextJS

*Pengantar: Arsitektur WebGIS, Frontend dan Backend*

### Menambahkan Komponen Peta pada NextJS

- Mengapa Maplibre?
- Instalasi Maplibre dan ReactMapGL pada NextJS
- Membuat komponen Peta
- Menambahkan Data GeoJSON pada Peta
- Kartografi web: Data-driven Styling

### Vector Tiles dengan Basisdata PostgreSQL

- Standar Baru OGC untuk Pertukaran Data Spasial
- Instalasi PostgreSQL dan PostGIS pada WSL
- Instalasi pgAdmin
- Mengunggah Data Spasial pada Basisdata
- Instalasi dan Pengaturan GeoREST-API
- Menggunakan Vector Tiles pada WebGIS NextJS
- *Trivia: PMTiles*

---

Topik-topik berikut baru dapat disampaikan setelah familiar dengan semua topik di atas

## Topik Lanjutan Pengembangan WebGIS

### Pengaturan Akses dan Keamanan Data

- Authentikasi dan Otorisasi
- Authentikasi sederhana dengan NextAuth
- Membuat halaman login dan signup
- Mengatur Sesi dan Akses Pengguna

### Membangun Backend dengan FastAPI

- Mengapa perlu backend?
- Instalasi FastAPI
- Koneksi dengan basisdata PostgreSQL menggunakan SQLAlchemy
- Membuat Query pada Basisdata
- Membangun REST API dengan FASTAPI
- Deployment aplikasi fullstack dengan Docker
