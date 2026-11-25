# SmartStudy Kids - Bank Soal Lengkap

Isi:
- 36 paket (kelas 1-6 x 6 mata pelajaran)
- 5,400 butir soal
- 3 materi per paket, masing-masing 50 soal
- 10 soal per percobaan
- Tingkat kesulitan: 20 mudah, 20 sedang, 10 menantang per materi
- Pilihan jawaban dan urutan soal diacak
- ID soal disimpan melalui bridge AndroidQuiz agar soal yang sudah tampil dihindari sampai bank materi habis

## Struktur
- `catalog.json`
- `packages/<nama-paket>.zip`
- Setiap ZIP berisi tepat: `manifest.json`, `index.html`, `style.css`, `script.js`

## Unggah ke GitHub
Salin `catalog.json` ke root repositori dan semua ZIP dari folder `packages/` ke folder `packages/` repositori.
URL unduhan pada katalog memakai branch `main` dan repositori `iezra84-net/smartstudy-kids-content`.

## Catatan pemeriksaan
Paket dibuat dengan format WebView lokal dan bridge `AndroidQuiz` yang sudah dipakai aplikasi. Sebelum rilis ke semua pengguna, lakukan uji impor dan kuis di HP untuk memverifikasi integrasi dengan versi aplikasi yang sedang dipakai.
