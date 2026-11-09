# Rencana Desain Tahap 0: Landing Page Skilqu Track C

Hasil Tahap 0 (tanpa kode halaman), diperbarui 9 Nov 2026. Disusun dari ketiga skill: **ui-ux-pro-max** (design system & aturan UX), **impeccable** (PRODUCT.md, arah visual, brief), **taste-skill** (jenis halaman, copy-lint, rencana layar). Isi teks lengkap ada di `Isi Landing Page Skilqu Track C v2.md`; fakta produk di `PRODUCT.md`.

---

## 1. Arah visual terpilih: Soft Cards (biru muda)

**Dipilih user** setelah melihat 3 gaya (A Soft Cards, B Bento, C Split + HP). Arah "Formulir Kampus" dari roll impeccable tidak dipakai; keputusan user menang atas roll.

**Sketsa acuan:** `.impeccable/mocks/v2/a-soft-cards.html` (screenshot: `a-soft-cards.png`).

**Ide utama:** halaman terasa ringan dan ramah. Latar biru muda bergradasi halus, isi produk ditunjukkan lewat kartu putih yang "melayang": kartu cheat sheet STAR di tengah, dikelilingi kartu kecil (Pertanyaan 2 dari 10, 100+ mahasiswa, stempel SIAP INTERVIEW).

**Yang dipertahankan dari Tahap 0 sebelumnya:**
- Amber hanya untuk tombol aksi dan stempel, tidak sebagai hiasan.
- Klik satu baris STAR → baris itu menonjol, baris lain meredup.
- Form CTA gaya "Penampang Berlabel": label "Email kamu" di atas, kolom dan tombol terpisah.

**Risiko yang dijaga:** gaya kartu melayang mudah terlihat seperti template SaaS. Penyeimbangnya: isi kartu adalah konten asli Skilqu (jawaban STAR, pertanyaan interview), bukan ikon fitur generik; kartu tidak diulang dengan pola yang sama di setiap bagian.

---

## 2. Design system

**Warna**

| Peran | Hex | Catatan |
|---|---|---|
| Tinta utama | `#0F2A4A` | Judul dan teks |
| Tinta sekunder | `#47607E` | Teks pendukung |
| Biru utama | `#3B82F6` | Aksen: kata kunci di H1, pil aktif, huruf S-T-A-R |
| Biru muda | `#E6F3FF` | Latar halaman (gradasi dari `#F3F9FF`) |
| Biru muda 2 | `#CFE7FF` | Titik penanda, latar ikon |
| Garis halus | `#D6E6F7` | Batas kolom dan pemisah baris |
| Kartu | `#FFFFFF` | Semua kartu |
| CTA | `#F59E0B` | Wajib dari modul; teks di atasnya `#1F1400` |
| Teks amber | `#B45309` | Stempel (kontras ≥ 4.5:1) |

**Huruf:** **Plus Jakarta Sans** untuk semua teks (permintaan user: font biasa). Judul 800, subjudul 700, teks 400–500. Teks isi minimal 16px di HP.

**Bentuk:** kartu radius 22px dengan bayangan lembut kebiruan; tombol dan kolom radius 14px; pil radius penuh.

**Aturan UX (checklist ui-ux-pro-max):** kontras ≥ 4.5:1, target sentuh ≥ 44px, ikon SVG garis (tanpa emoji), label form terlihat, error di bawah kolomnya, semua gerakan berhenti saat *reduce motion*, dicek di 375 / 768 / 1024 / 1440px.

---

## 3. Rencana layar (taste-skill)

**Jenis halaman:** software (platform belajar), karena hanya jenis ini yang mengizinkan kartu animasi berulang dan angka yang menghitung naik.

| # | Bagian | Isi & visual | Motion | Tinggi |
|---|---|---|---|---|
| 1 | **Hero** | Logo + pil "Gratis · 15 menit · Teknik STAR" di pojok kanan atas (bukan di atas H1). H1 dengan "Cara Jawabnya" biru, pil alur Pahami → Latihan → Siap interview, sub-headline, form email + **Ambil Gratis**, 3 kalimat penenang. Kanan: kartu cheat sheet STAR + kartu kecil melayang + stempel. | Pil alur menyala bergantian (2); cheat sheet terisi baris demi baris lalu stempel muncul (3); Hero masuk sekali saat dibuka | 1 layar |
| 2 | **Masalah** | 3 kartu "momen gagal" dengan ikon SVG garis. Kalimat penutup besar. | Kalimat penutup menyala kata demi kata saat di-scroll (4) | 1 layar |
| 3 | **Solusi** | Sebelum vs Sesudah (klik baris STAR untuk isolasi). Isi Free Starter Kit (3 butir). Tabel YouTube vs Bootcamp vs Skilqu. CTA ulangan. | Kartu "Cek jawaban STAR-mu" yang centangnya bertambah sampai 4/4 (5) | 2 layar |
| 4 | **Trust & FAQ** | Cuplikan halaman cheat sheet (bawahnya buram). Angka "100+ mahasiswa ambil tiap bulan". Kartu paket Free vs Skilqu Pass (Rp49.000/bulan, batal kapan saja, Mock Interview "segera hadir"). FAQ 5 pertanyaan. | Angka 100+ menghitung naik saat terlihat (6) | 2 layar |
| 5 | **Form akhir** | Hook penutup, H2, form Nama · Email (terisi dari Hero) · Fokus Track (terpilih), tombol **Kirim ke Email Saya**, kalimat penenang. Setelah terkirim: stempel "TERKIRIM" + pesan cek email. | Stempel muncul setelah kirim berhasil | 1 layar |
| — | Footer | © Skilqu · kontak · Kebijakan Privasi · kredit foto (satu baris) | — | — |

**Selalu ada:** tombol sticky "Ambil Cheat Sheet Gratis" di HP setelah lewat Hero, hilang saat form akhir terlihat. Semua tombol terangkat saat disorot dan turun saat diklik (1).

**Motion 5** memakai "Cek jawaban STAR-mu" (centang mandiri), bukan rapor/skor, karena penilaian adalah fitur Skilqu Pass yang belum ada.

**Copy-lint taste-skill:** bersih; satu FAIL hanya dari label penomoran draft yang tidak tampil di halaman.

---

## 4. Batasan

- Satu tujuan: daftar Free Starter Kit. Tanpa menu navigasi, popup, atau animasi pembuka.
- Tombol CTA terlihat sejak detik pertama di laptop dan HP.
- Tidak ada testimoni, rating, logo media, atau angka karangan. Angka hanya dari business case modul.
- Foto (kalau dipakai) stand-in berlisensi bebas, dicatat di laporan sebagai ilustrasi.
- Tanpa efek shader/3D berat.

## 5. Masih terbuka

- Di HP, kartu-kartu kecil yang melayang di Hero disederhanakan (kemungkinan hanya kartu cheat sheet + stempel) supaya tidak ramai dan tombol tetap terlihat.
- Link Google Form (ID entry) dan link S.id diisi kelompok setelah halaman jadi.
