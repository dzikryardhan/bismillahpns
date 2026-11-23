# Bismillah PNS - Platform Belajar & Simulasi CPNS SKD

Aplikasi pendamping belajar harian dan simulasi ujian CAT SKD CPNS berbasis web.

## Fitur Utama
- **Hari Ini**: Target materi harian, checklist belajar, streak konsistensi 4 minggu, dan hitung mundur ujian.
- **Jadwal**: Rotasi belajar terstruktur mingguan (TWK, TIU, TKP, dan Tryout).
- **Materi**: Panduan lengkap dan link modul SKD (Kitab Mini SKD, Modul 10 Nasionalisme, Handbook TIU, dsb.).
- **Tryout CAT**: Simulasi ujian berbasis CAT BKN dengan timer dan sistem penilaian sesuai passing grade resmi (TWK, TIU, TKP).
- **Video**: Video kurasi dari pengajar CPNS terkemuka (Al Faiz, Sang Tutor, dsb.).
- **Progres**: Grafik perkembangan belajar, riwayat skor tryout, dan indikator kesiapan ambang batas.
- **Penyimpanan Lokal**: Data otomatis tersimpan di peramban masing-masing pengguna (`localStorage`).

## Cara Menjalankan Secara Lokal
Cukup buka file `index.html` langsung di peramban web apa pun (Chrome, Edge, Firefox, Safari) atau gunakan live server:
```bash
# Menggunakan npx serve (opsional)
npx serve .
```

## Hosting di Cloudflare Pages
1. Push repository ini ke akun GitHub Anda.
2. Buka dashboard [Cloudflare](https://dash.cloudflare.com/) > **Workers & Pages** > **Create application** > **Pages** > **Connect to Git**.
3. Pilih repository GitHub ini.
4. Pada build settings:
   - **Framework preset**: `None`
   - **Build command**: *(kosongkan)*
   - **Build output directory**: `.` (atau biarkan default)
5. Klik **Save and Deploy**.
