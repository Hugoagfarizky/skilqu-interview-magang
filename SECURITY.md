# Kebijakan Keamanan

## Yang perlu diketahui

Proyek ini adalah **tugas kuliah**: situs statis (HTML, CSS, JavaScript) tanpa backend, tanpa database, dan tanpa akun pengguna. Data pendaftaran diproses di Lynk.id, bukan di repo ini.

## Melaporkan celah keamanan

Kalau kamu menemukan masalah keamanan (misalnya XSS, tautan berbahaya, atau data sensitif yang tidak sengaja ter-commit):

- **Jangan** membuka issue publik.
- Kirim email ke **nugrahaagfarizky@gmail.com** dengan subjek `[SECURITY] skilqu-interview-magang`.
- Sertakan: langkah reproduksi, dampak, dan saran perbaikan kalau ada.

Karena ini proyek tugas, balasan diberikan sebaik mungkin dalam **7 hari kerja**. Setelah diperbaiki, kamu akan disebut sebagai pelapor kalau memang diinginkan.

## Cakupan

| Termasuk | Tidak termasuk |
| --- | --- |
| `index.html`, `privacy.html`, `assets/` | Layanan pihak ketiga (Netlify, Lynk.id, Google Fonts, YouTube) |
| Kebocoran data pribadi di repo | Serangan fisik atau social engineering |

## Versi yang didukung

Hanya branch `main` yang diperbarui. Tidak ada rilis berversi.
