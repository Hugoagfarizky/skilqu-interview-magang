# Konsep Feed Carousel Skilqu (Modul 3: Content Making & A/B Testing)

Track C (Interview). 1 carousel, 7 slide, ukuran 1080×1350 (4:5). Dua versi hanya beda di **Slide 1 (cover)**; Slide 2–7 dan caption sama persis.

> Yang ditulis dalam [kurung siku] wajib diisi atau dicek kelompok dulu.

---

## 1. A/B Experiment Card

| Komponen | Isi |
|---|---|
| **1. Masalah / evidence awal** | Landing page Modul 2 sudah siap dan sekarang CTA-nya ke produk Free Starter Kit Rp0 di Lynk.id. Masalahnya ada di trafik: Outbound CTR konten organik Skilqu baru 2,0% (20 klik dari 1.000 impressions). Audiens seperti Nadya cenderung cuma nge-*save* postingan tanpa klik link. |
| **2. Variabel uji (hanya 1)** | Slide 1 (cover carousel): kalimat hook dan visualnya. |
| **3. Versi A (Control)** | **Ikut tren ("newsjacking"):** "Lagi Ramai yang **Mundur**, Kamu Sudah Siap **Maju Interview**?" + "Jangan sampai kesempatanmu ikut terlewat karena belum siap menjawab pertanyaan HR." Foto tokoh publik sedang hormat, dipilih kelompok (final: frame Figma "Skilqu · Cover interview · 1 dari 8"; tombol "Geser" sudah disamakan dengan B). |
| **4. Versi B (Challenger)** | **Rasa sakit yang relatable:** foto wisudawan menutup muka + "Toga udah dibalikin. **Kerjaan belum dateng.**" + "Jangan sampai kesempatanmu ikut terlewat karena belum siap menjawab pertanyaan HR." (frame "Cover B4 – Toga udah dibalikin"). |
| **5. Hipotesis** | Jika Slide 1 diubah dari hook yang menumpang tren berita "mundur" (A) menjadi hook yang menggambarkan langsung keadaan fresh graduate yang belum dapat kerja (B), maka Outbound CTR akan naik minimal +50%, dari 2,0% menjadi ≥ 3,0% (klik s.id ÷ impressions, minimal 300 impressions per versi). Alasannya: hook tren memancing rasa penasaran, tetapi hook B lebih cocok dengan persona Nadya, sehingga rasa takut tertinggal (*fear of missing out / loss aversion*) lebih kuat mendorong klik untuk menyiapkan interview. |
| **6. KPI utama & target** | Outbound CTR = (klik link s.id ÷ total impressions) × 100%. Target ≥ 3,0%, minimal 300 impressions per versi. Pendukung: Save Rate, High-Intent Engagement Rate, dan pendaftar Starter Kit di Lynk.id. |
| **7. Kondisi kontrol** | 1) Slide 2–7, visual di dalamnya, dan caption 100% identik. Bedanya hanya link s.id, karena itu alat pelacakan, bukan variabel kreatif. 2) Jam tayang sama: [19.00] WIB. 3) Durasi amatan sama, 48 jam per versi. 4) Tujuan link sama: landing page Skilqu, lalu ke Lynk.id. |

**Jadwal (Model 1 – Sequential Feed Post):**

| Versi | Tayang | Diamati sampai | Link di postingan |
|---|---|---|---|
| A | Rabu, 18 Nov 2026, [19.00] WIB | Jumat, 20 Nov, [19.00] | s.id/skilqu-[kelX]-a |
| B | Kamis, 19 Nov 2026, [19.00] WIB | Sabtu, 21 Nov, [19.00] | s.id/skilqu-[kelX]-b |

Link s.id-nya diarahkan ke:
- A: `https://skilqu-interview-magang.netlify.app/?utm_source=ig&utm_medium=carousel&utm_content=hook_control_A`
- B: `https://skilqu-interview-magang.netlify.app/?utm_source=ig&utm_medium=carousel&utm_content=hook_variant_B`

---

## 2. Slide 1: Cover (variabel uji)

Kerangka kedua cover sama: logo "S skilqu" di kiri atas, penanda "1/7" di kanan atas, dan isyarat "Geser →" di kanan bawah. Yang berbeda hanya kalimat hook dan visual utamanya.

### Cover A (Control): cerita personal resign
- **Visual:** foto orang muda (Indonesia/Asia Tenggara) mengisi ±60% bagian atas. Misalnya keluar kantor sambil membawa kardus barang, atau duduk di depan laptop membuka lowongan. Foto stok berlisensi bebas (Unsplash/Pexels), dan di laporan dilabeli sebagai ilustrasi.
- **Hook (11 kata):**
  **"Resign Bulan Ini, Mau Cari Kerja Baru?"** (besar; kata *Resign* berwarna amber)
  "Siapin jawaban interview-nya dulu." (baris kedua, lebih kecil)
- **Latar teks:** pita navy #0F172A di bagian bawah foto, teks putih.

### Cover B (Challenger): data BPS
- **Visual:** latar navy #0F172A dengan angka **"1 Juta+"** sangat besar berwarna amber #F59E0B. Boleh ditambah barisan ikon orang (garis) di belakangnya.
- **Hook (10 kata):**
  **"1 Juta+ Sarjana Nganggur di 2026."**
  "Yakin kamu siap interview?" (baris kedua)
- **Baris sumber kecil:** "Sumber: BPS, Februari 2026"

### Alternatif cover (versi 2, 17 Nov — foto nyeleneh + gaya media IG)
Referensi gaya cover: @folkative (foto di atas, panel putih dengan teks hitam besar di bawah), @asumsico (foto penuh, huruf kapital tebal, satu frasa diberi warna), @ussfeeds (blok kuning besar di bawah foto), dan @mojokdotco (foto gelap dengan satu kalimat nyeleneh). Alternatif versi 1 (kutipan HRD, POV, peringatan, 1 dari 7, kartu berita, checklist) sudah dihapus.

Pilih **satu** cover untuk Feed A dan **satu** untuk Feed B. Tema tiap feed harus tetap: A = resign + foto orang, B = data BPS. Sekarang cover B juga memakai foto.

| Kode | Foto | Hook | Gaya |
|---|---|---|---|
| A1 | Pria membawa kardus keluar kantor | "Resign Bulan Ini, Mau Cari Kerja Baru?" + "Siapin jawaban interview-nya dulu." | Asli |
| A2 | Pria teriak ke telepon | "“SAYA RESIGN!!”" + "…TERUS PAS INTERVIEW **DITANYA KENAPA?**" | Asumsi |
| A3 | Pria melempar kertas sambil tertawa | Label "HARI TERAKHIR KERJA" + "RESIGN RASANYA KAYAK GINI." + "Interview berikutnya? Beda cerita." (di blok amber) | USS Feed |
| A4 | Kardus menutupi kepala (hitam-putih) | "Ditanya HRD **‘kenapa resign?’**, rasanya pengen ngumpet." | Folkative |
| A5 | Kepala monitor di sofa (gelap) | "Resign, rebahan 3 bulan, tiba-tiba **dipanggil interview.**" | Mojok |
| B1 | (tanpa foto) | "1 Juta+ Sarjana Nganggur di 2026." + "Yakin kamu siap interview?" | Asli |
| B2 | Lautan topi wisuda dari atas + lingkaran amber "kamu?" | "1 JUTA+ SARJANA NGANGGUR." + "Coba cari kamu di foto ini." | Asumsi |
| B3 | Wisudawati memegang papan "I'M DONE!" | "Lulus ✓ / Kerja ✗" + "Posisi 1 juta+ sarjana di 2026." | Foto penuh + ikon |
| B4 | Wisudawan menutup muka | "Toga udah dibalikin. **Kerjaan belum dateng.**" + "1 juta+ sarjana nganggur." | Foto penuh |
| B5 | Foto arsip antrean hitam-putih (NYPL) | "Antre kerja 2026: **1 juta+ sarjana** di depan kamu." | Folkative |

Semua cover B memakai baris "Sumber: BPS, Februari 2026"; B5 ditambah "Foto arsip: NYPL".

#### Ronde 3 (format parodi & foto absurd) — di Figma, di sebelah kanan ronde 2
Referensi: hashtag #carouseldesign (judul raksasa + stiker ala poster), @ryanair (parodi formulir/chat), dan @duolingo (parodi tampilan kuis). Polanya: cover yang **meniru format lain** (notifikasi, kuis, surat) atau memakai **foto absurd** dengan judul besar. Disusun dengan skill `ui-ux-pro-max:banner-design`.

| Kode | Foto | Hook | Gaya |
|---|---|---|---|
| A6 | Dua orang berdandan badut di depan laptop | "KERJA DI KANTOR LAMA RASANYA KAYAK SIRKUS." + stiker "Tapi jangan bilang gitu ke HRD." | Neubrutal (latar amber, garis tebal, bayangan keras) |
| A7 | Pria berjas berdiri di air (hitam-putih) | "RESIGN TANPA PERSIAPAN INTERVIEW =" + "**TENGGELAM.**" | Editorial |
| A8 | Orang berkantong kertas di kepala, minum es kopi | Notifikasi email palsu "HRD PT Nusantara Jaya: Undangan interview besok, 09.00 WIB" + "Hari ke-1 setelah resign: **Belum siap jawab apa-apa.**" | Parodi notifikasi |
| A9 | Pomeranian berkacamata di depan tablet (jadi "HRD") | "HRD: ‘Kenapa kamu resign?’" + "Pilih jawaban yang aman:" A. Bos saya toxic / B. Gajinya kecil banget / C. Pengen rebahan dulu + "Spoiler: ketiganya bikin gugur." | Parodi kuis ala Duolingo |
| B6 | Kucing di atas mesin fotokopi + stempel "SUDAH DILEGALISIR" | "Fotokopi ijazah **ke-50** bulan ini." + "1 juta+ sarjana masih nganggur." | Foto penuh + stempel |
| B7 | Foto vintage anjing berbaju membaca surat + kartu surat "DITOLAK" | "Jangan sampai surat ini **nyampe ke kamu.**" + "1 juta+ sarjana masih nganggur." | Parodi surat penolakan |
| B8 | Corgi (foto dalam kartu bergaris tebal) | Stiker "Saingan: 1 juta+ sarjana nganggur" + "DIA UDAH SIAP INTERVIEW." + "**KAMU?**" | Neubrutal (latar biru muda) |
| B9 | Pria berjas di air, diberi efek biru (duotone) | "Tenggelam di antara" + "**1 JUTA+**" + "sarjana nganggur?" | Editorial / duotone |

Semua cover B ronde 3 memakai baris "Sumber: BPS, Februari 2026". "PT Nusantara Jaya" di A8 adalah nama perusahaan fiktif.

Catatan:
- Foto B6 memperlihatkan papan nama toko fotokopi asli beserta nomor teleponnya. Kalau mau aman, buramkan dulu sebelum diposting.
- Foto B7 aslinya kartu pos vintage, jadi ada tulisan bawaan di dalam foto.

**Kredit foto ronde 3 (Unsplash, Unsplash License):** cek nama fotografer di halaman masing-masing:
- A6: unsplash.com/photos/cv-g98cBU6o
- A7 dan B9: unsplash.com/photos/lz-eXV7zmyU
- A8: unsplash.com/photos/dvypCjZv3QI
- A9: unsplash.com/photos/gySMaocSdqs
- B6: unsplash.com/photos/hRTalolieZw
- B7: unsplash.com/photos/MkNt53764m0
- B8: unsplash.com/photos/CmypobG8FOY

**Kredit foto (Unsplash, Unsplash License)** — cantumkan di laporan sebagai ilustrasi:
- A1: Vitaly Gariev
- A2: Icons8 Team
- A3: @silverkblack [cek nama fotografer di unsplash.com/photos/0yVI5Dd0uMU]
- A4: Ante Hamersmit
- A5: Paris Bilal
- B2: Joshua Hoehne
- B3: chichi1813
- B4: Etan Jamz
- B5: New York Public Library (NYPL)

PNG alternatif ada di `Modul 3 Carousel/Alternatif Cover/`. Kalau cover yang dipilih bukan A1/B1, perbarui juga baris Versi A/B di Experiment Card dan gambar perbandingan untuk laporan.

---

## 3. Slide 2–7 (identik di A dan B)

### Slide 2: Masalah yang relate (Retain)
- Label kecil: *Pertanyaan yang hampir pasti keluar*
- Bubble chat **HRD:** "Ceritakan tantangan yang pernah kamu hadapi, dan gimana kamu menyelesaikannya."
- Bubble chat **Kamu:** "Hmm… saya pernah ikut kepanitiaan, di situ saya belajar kerja sama tim."
- Penutup: **"Jawaban kayak gini bikin HRD susah ingat kamu. Nggak ada cerita, nggak ada bukti."**

### Slide 3: Kenalan sama STAR (Retain)
- Judul: **"Pakai rumus STAR biar jawabanmu punya alur"**
- **S – Situasi:** kapan dan di mana kejadiannya. Cukup 1 kalimat.
- **T – Tugas:** apa tanggung jawabmu saat itu.
- **A – Aksi:** apa yang *kamu* lakukan. Ini bagian paling panjang.
- **R – Hasil:** apa hasilnya. Pakai angka kalau bisa.

### Slide 4: Sebelum vs sesudah (Retain)
- Judul: **"Bedanya kelihatan banget"**
- Kartu abu, ikon silang. **Jawaban biasa:** "Saya pernah ikut kepanitiaan dan belajar kerja sama tim."
- Kartu biru, ikon centang. **Jawaban STAR:** "Saat jadi koordinator acara, dua divisi berebut anggaran **(S)**. Saya harus memastikan acara tetap jalan **(T)**. Saya ajak rapat dan membagi ulang anggaran sesuai prioritas **(A)**. Acara berjalan sesuai jadwal dan dana masih tersisa 10% **(R)**."
- Penutup: **"Jawaban kedua punya bukti. Itu yang dicari HRD."**

### Slide 5: 3 aturan cepat (Reward / quick win)
- Judul: **"3 aturan biar jawaban STAR-mu nempel"**
1. **Satu huruf, 1–2 kalimat.** Total jawaban sekitar 1 menit.
2. **Aksi paling panjang.** Pakai "saya", bukan "kami".
3. **Tutup pakai angka:** waktu, jumlah orang, persen, atau rupiah.

### Slide 6: Jembatan ke landing page
- Judul: **"Itu baru 1 dari 10 pertanyaan"**
- Visual: kartu cheat sheet. Pertanyaan 1 terbuka, sisanya diburamkan (misalnya "Ceritakan tentang dirimu", "Apa kekuranganmu?" yang ditandai *jebakan*, "Kenapa kami harus memilihmu?").
- Teks: "Baca slide aja belum cukup. Kamu perlu latihan nyusun jawabanmu sendiri."
- "Di **Free Starter Kit**: video 15 menit Teknik STAR + cheat sheet 10 pertanyaan + contoh jawaban dari pengalaman kampus."

### Slide 7: CTA
- Judul: **"Ambil gratis (Rp0) sekarang"**
- Kotak amber besar: **"Ketik s.id/skilqu-[kelX]-a"** (di versi B: **-b**)
- Di bawahnya: "Video 15 menit + cheat sheet 10 pertanyaan interview"
- Baris kecil: "Link juga ada di caption · 100% gratis · Tanpa kartu kredit"

> Catatan: link di caption feed Instagram tidak bisa diklik, jadi link s.id harus pendek dan mudah diketik. Kalau mau, tiap feed juga dibagikan ke Story dengan stiker link (A di hari A, B di hari B). Caranya harus sama untuk kedua versi.

---

## 4. Caption (identik, kecuali link)

> Kalau HRD tanya "ceritakan tantangan yang pernah kamu hadapi", jawabanmu udah ada strukturnya belum?
>
> Teknik STAR bikin jawabanmu punya alur: Situasi, Tugas, Aksi, Hasil. Di Free Starter Kit Skilqu kamu dapat:
> ✔ Video 15 menit Teknik STAR
> ✔ Cheat sheet 10 pertanyaan interview yang paling sering keluar (termasuk pertanyaan jebakan)
> ✔ Contoh jawaban dari pengalaman kampus
>
> Lebih ringkas dari tutorial YouTube 2 jam, dan langsung bisa dipakai latihan.
>
> Ambil gratis (Rp0): s.id/skilqu-[kelX]-a
>
> #interviewmagang #tipsinterview #teknikSTAR #pertanyaaninterview #magang #freshgraduate #carikerja #persiapaninterview

Di versi B, link-nya diganti `s.id/skilqu-[kelX]-b`. Hashtag diambil dari keyword Modul 1 (pertanyaan interview magang, cara menjawab pertanyaan interview, teknik STAR). [Cek ulang dengan hasil riset Modul 1 kelompok.]

---

## 5. Arah visual

- **Warna (Brand Guidelines Skilqu, Modul 00):** Navy #0F172A dan Royal Blue #2563EB untuk identitas; Amber #F59E0B untuk kata kunci hook dan kotak CTA; latar #FFFFFF / #F8FAFC untuk slide penjelasan.
- **Pola slide:** Slide 1 dan 7 berlatar navy dan kontras tinggi. Slide 2–6 berlatar terang.
- **Gaya:** Soft Cards seperti landing page: kartu putih membulat dengan bayangan halus, motif kartu cheat sheet STAR, font Plus Jakarta Sans.
- **Ukuran teks:** judul ±64–96 px, isi ≥ 36 px di kanvas 1080 px, supaya tetap terbaca di HP. Maksimal ±40 kata per slide.
- **Elemen tetap:** logo "S skilqu" dan nomor slide di tiap slide. Ikon SVG garis, tanpa emoji di slide.
- **Produksi:** di Figma (frame 1080×1350), lalu diekspor ke PNG.

---

## 6. Risiko & catatan untuk laporan

1. **Hook A tidak cocok dengan persona.** Nadya adalah mahasiswa tingkat akhir/fresh graduate yang belum pernah bekerja, sementara landing page membahas interview *magang*. Hook resign bisa menarik audiens yang berbeda, dan klik dari mereka mungkin tidak berlanjut ke pendaftaran. Contoh di Slide 2–7 sengaja dibuat umum (pertanyaan "tantangan"), tapi contoh STAR tetap dari kampus supaya nyambung dengan landing page.
2. **Yang diuji adalah cover secara utuh.** Versi A dan B berbeda di kalimat dan visual (foto vs angka). Ini sesuai definisi variabel di modul ("Hook kalimat dan visual pada Slide 1"), jadi kesimpulannya berlaku untuk cover secara utuh, bukan untuk kalimatnya saja.
3. **Masa tayang A dan B tumpang tindih 24 jam** (19–20 Nov). Klik tetap terpisah karena link-nya berbeda, tapi follower yang sama bisa melihat kedua postingan.
4. **Ukuran sampel kecil.** Kalau kliknya masih belasan, simpulkan sebagai *directional signal*, bukan hasil yang signifikan.
5. **Cover A memakai foto tokoh publik (keputusan kelompok, 18 Nov).** Foto ini kemungkinan bukan milik kelompok (hak cipta media), dan bersama kata "mundur" bisa dibaca sebagai komentar politik. Risikonya:
   - Iklan Meta di Modul 5 bisa ditolak karena menyangkut tokoh publik atau isu politik. Kalau A menang, siapkan versi dengan foto stok sebelum dipasang sebagai iklan.
   - Keterlibatan dan klik mungkin terdorong oleh tokohnya, bukan oleh hook-nya. Ini perlu disebut saat menganalisis hasil.
6. **Cover B tidak lagi memakai data BPS.** Baris "Sumber: BPS" tidak diperlukan di B. Data BPS tetap bisa dipakai di bagian latar belakang laporan.

---

## 7. Sumber data

- **Cover B (dipakai):** BPS, Februari 2026. Lulusan D4/S1/S2/S3 yang menganggur lebih dari 1 juta orang. [Project Multatuli](https://projectmultatuli.org/sarjana-di-indonesia-berakhir-menjadi-pengangguran/) (30 Jul 2026) menyebut 1.033.737 orang (14,3% dari total penganggur). [RRI](https://rri.co.id/biak/nasional/2685089/sarjana-yang-menganggur-di-indonesia-tembus-1-juta-jiwa) (27 Agu 2026) menyebut 1.010.652 orang. Kedua angka di atas 1 juta, jadi di cover ditulis **"1 Juta+"**. Rilis resmi BPS: [TPT Februari 2026 sebesar 4,68%](https://www.bps.go.id/id/pressrelease/2026/05/05/2574/tingkat-pengangguran-terbuka--tpt--sebesar-4-68-persen--rata-rata-upah-buruh-sebesar-3-29-juta-rupiah-.html). [Cek angka persisnya di publikasi BPS "Keadaan Angkatan Kerja di Indonesia Februari 2026" sebelum laporan dikumpulkan.]
- **Tidak dipakai:**
  - "75% Gen Z gugup saat interview": tidak ditemukan sumbernya.
  - "79% / 8 dari 10 Gen Z cemas interview": salah kutip. Di [SHRM](https://www.shrm.org/mena/enterprise-solutions/insights/gen-z-job-market-challenges-opportunities-2025) (16 Jan 2025), angka 79% itu soal semua pencari kerja di AS yang cemas pada *pasar kerja* (data Greenhouse 2024), bukan Gen Z dan bukan soal interview.
