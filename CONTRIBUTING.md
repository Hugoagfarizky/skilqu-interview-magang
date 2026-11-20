# Panduan Kontribusi

Terima kasih sudah mau membantu. Proyek ini kecil dan sengaja dibuat sederhana: HTML, CSS, dan sedikit JavaScript, tanpa framework dan tanpa build step.

> Ini tugas kuliah (Mata Kuliah Pemasaran Digital, ITS). Skilqu adalah studi kasus fiktif, jadi kontribusi diarahkan ke kualitas halaman, bukan ke fitur produk.

## Menjalankan di komputer sendiri

Beberapa script memakai ES module yang tidak jalan dari `file://`, jadi pakai server lokal:

```bash
python -m http.server 8480
```

Lalu buka http://localhost:8480.

## Sebelum mengirim perubahan

- Cek tampilan di lebar **375px** (prioritas utama, mobile-first) dan **1440px**.
- Pastikan tombol CTA tetap terlihat di layar pertama dan target sentuh minimal 44px.
- Jangan menambah dependency atau build step baru.
- Hormati `prefers-reduced-motion`: semua animasi harus berhenti.
- Jaga teks tetap jujur: jangan menambah klaim, angka, atau testimoni yang tidak ada di `PRODUCT.md`.

## Gaya kode

- Indentasi 2 spasi, satu properti per baris di CSS.
- Nama class mengikuti pola yang sudah ada di `assets/system.css` (lihat `DESIGN.md`).
- JavaScript: `const`/`let`, tanpa `var`, dan komentar singkat untuk logika yang tidak jelas.
- Warna, spasi, dan tipografi diambil dari token desain, bukan nilai acak.

## Alur kontribusi

1. Buat branch: `git checkout -b fix/nama-singkat`.
2. Commit dengan pesan jelas, contoh: `Hero: perbaiki kontras teks tombol CTA`.
3. Buka pull request ke `main` dan jelaskan **apa** dan **kenapa**.
4. Satu PR untuk satu hal. PR besar lebih sulit ditinjau.

## Melaporkan bug atau ide

Buka issue dengan menyertakan: halaman/bagian yang bermasalah, langkah reproduksi, perangkat atau browser, dan screenshot kalau ada.

Untuk masalah keamanan, ikuti `SECURITY.md`, jangan buka issue publik.

## Lisensi kontribusi

Dengan mengirim pull request, kamu setuju kontribusimu dirilis di bawah [MIT License](LICENSE).
