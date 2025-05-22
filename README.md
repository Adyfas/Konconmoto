# Koncomoto Dashboard

## Pengenalan
Koncomoto Dashboard adalah aplikasi web yang dirancang untuk membantu tim Koncomoto dalam mengelola dan berkomunikasi dengan klien secara efisien. Aplikasi ini menyediakan antarmuka yang intuitif untuk mengelola reminder, pembayaran, dan komunikasi dengan klien.

## Fitur Utama
1. **Manajemen Klien**
   - Pembuatan pricing guide untuk menyimpan data klien
   - Penyimpanan informasi lengkap klien (nama, nomor telepon, email, source)
   - Sistem pelabelan klien untuk pengorganisasian yang lebih baik

2. **Pengelolaan Invoice**
   - Pembuatan dan pengiriman invoice otomatis
   - Integrasi dengan sistem komunikasi untuk pengiriman invoice
   - Tracking status invoice

3. **UI/UX Modern**
   - Desain minimalis dan modern
   - Antarmuka yang intuitif dan responsif
   - Penggunaan ikon yang informatif
   - Warna dan layout yang profesional

## Teknologi yang Digunakan
- **Frontend**: Next.js 15.2.4
- **UI Framework**: Tailwind CSS
- **State Management**: Zustand
- **Database**: Supabase
- **Email Service**: Nodemailer
- **Animasi**: Framer Motion
- **Icons**: FontAwesome, Lucide React

## Persyaratan Sistem
- Node.js (versi terbaru LTS)
- npm atau yarn
- Koneksi internet untuk instalasi dependensi

## Cara Instalasi

1. Clone repository
```bash
git clone https://github.com/Adyfas/Konconmoto
cd koncomoto/client
```

2. Install dependensi
```bash
npm install
# atau
yarn install
```

3. Konfigurasi environment
Buat file `.env.local` dan isi dengan konfigurasi yang diperlukan:
```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_key
# Tambahkan konfigurasi lain yang diperlukan
```

## Cara Menjalankan

1. Mode Development
```bash
npm run dev
# atau
yarn dev
```

2. Mode Production
```bash
npm run build
npm run start
# atau
yarn build
yarn start
```

## Script Tersedia
- `npm run dev` - Menjalankan aplikasi dalam mode development
- `npm run build` - Build aplikasi untuk production
- `npm run start` - Menjalankan aplikasi yang sudah di-build
- `npm run lint` - Menjalankan linter untuk memeriksa kode
- `npm run warm` - Menjalankan warm-up routes
- `npm run dev:with-warmup` - Menjalankan development server dengan warm-up routes

## Struktur Proyek
```
client/
├── components/     # Komponen React yang dapat digunakan kembali
├── pages/         # Halaman-halaman aplikasi
├── public/        # Aset statis
├── styles/        # File CSS dan styling
└── utils/         # Fungsi utilitas dan helpers
```

## Kontribusi
Untuk berkontribusi pada proyek ini:
1. Fork repository
2. Buat branch fitur baru
3. Commit perubahan Anda
4. Push ke branch
5. Buat Pull Request

## Kontak
+62 831-8271-9413 (adyfas)

# Fitur
 1. Admin dapat membuat sebuah pricing guge untuk menyimpan sebuah data client dari mulai nama, nomor telepon, email, dan source
 2. Selain bisa membuat sebuah pricing guge admin juga bisa melihat semua client yang sudah terdaftar dan bisa menambahkan label di setiap clientnya
 3. Di bagian View Client admin juga bisa melanjutkan sebuah proces untuk pengiriman invoice ke client, admin hanya klik saja tombol berbentuk seperti kertas dan ada pesawat di atasnya, itu akan mengirimkan semua data mulai dari nama, nomor telepon, email, dan source dan masuk ke page Pembuatan Invoice


 # UI/UX
 Untuk design dari dashboard admin ini sangat minimalis dan modern mulai dari dari warnanya, bentuknya dan juga icon-icon yang dapat melengkapi design nya agar semakin bagus 

 
