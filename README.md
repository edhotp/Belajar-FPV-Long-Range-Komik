# Terbang Jauh, Pulang Selamat! — Komik Anime Interaktif FPV Long Range

Bagian dari **SkyFlux FPV Learning Series** · dibuat oleh **@skyfluxfpv**

Belajar FPV Long Range dari nol lewat komik anime interaktif berbahasa Indonesia:
satu klik, satu panel — lengkap dengan dua lab yang bisa digeser-geser, kuis di tiap episode,
dan checklist lapangan.

Seluruh materi diambil dari seri tulisan
[FPV Long Range Mastery](https://github.com/edhotp/Belajar-FPV-Long-Range).
Komik ini adalah pengantar; modul aslinya memuat detail, diagram dan daftar rujukan lengkap.

## Isi

| Season | Episode | Topik | Materi |
|---|---|---|---|
| 1 · Fondasi | EP 1 — Mimpi terbang jauh | Apa itu FPV long range, tiga pilar, tangga skill | Modul 1 |
| 1 · Fondasi | EP 2 — Bongkar isi quad | Frame, motor, prop, FC, ESC, GPS, antena | Modul 2 |
| 1 · Fondasi | EP 3 — Tali tak terlihat | RC link, packet rate, LQ vs RSSI, mitos power | Modul 3 + 12 |
| 1 · Fondasi | EP 4 — Mata di langit | Video analog vs digital, antena goggles, OSD | Modul 4 |
| 1 · Fondasi | EP 5 — Tangki bensin | Li-Ion, 6S2P, tegangan per sel, sag, pengisian | Modul 5 |
| 2 · Rakit & aman | EP 6 — Rakit dengan kepala dingin | Urutan build, smoke stopper, bind, bench test | Modul 6 |
| 2 · Rakit & aman | EP 7 — Kalau tali putus | Failsafe dua tahap, GPS Rescue, uji failsafe | Modul 7 |
| 2 · Rakit & aman | EP 8 — Terbang perdana | Checklist maiden, mode ANGLE, membaca OSD | Modul 8 |
| 2 · Rakit & aman | EP 9 — Lulus tiga kali | Shakedown lima tahap, bench test RF, walk-range | Modul 9 + 12 |
| 3 · Misi | EP 10 — Hitung dulu, terbang kemudian | Perencanaan misi, anggaran baterai 45/45/10, angin | Modul 10 |
| 3 · Misi | EP 11 — Aturan main | Regulasi dan etika terbang | Modul 11 |
| 3 · Misi | EP 12 — Terbang jauh, pulang selamat | Hari misi, keputusan di udara, tiga aturan emas | Cheat Sheet + Modul 10 |

Tambahan: **Lab Link** (margin sinyal terhadap jarak, antena, packet rate, power dan halangan),
**Lab Baterai** (anggaran misi dengan angin dan titik putar balik), tabel **contekan**,
**checklist pre-flight** yang bisa dicentang, log cerita, versi teks, putar otomatis, dan layar penuh.

## Karakter

- **Arka** — pilot (kamu).
- **Kak Nara** — mentor long range.
- **Sena** — observer.
- **Flux** — roh flight controller, maskot seri ini.
- Para pengganggu: **Loso** (link putus), **Sago** (baterai anjlok), **Tofan** (angin lawan), **Buki** (bukit penghalang).

## Cara menerbitkan ke GitHub Pages

Seluruh situs adalah satu berkas `index.html` — tanpa build, tanpa dependensi.

1. Buat repositori publik baru di akun GitHub-mu.
2. Unggah `index.html` dan `README.md` ke akar branch `main`.
3. Buka **Settings** repositori → **Pages**.
4. Di **Build and deployment** → **Source**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.

## Kontrol pembaca

| Aksi | Cara |
|---|---|
| Lanjut | Klik panel, `Spasi` atau `→` |
| Kembali | Klik sisi kiri panel atau `←` |
| Log cerita | `L` |
| Putar otomatis | `A` |
| Versi teks | `T` |
| Layar penuh | `F` |
| Tutup episode | `Esc` |

## Catatan

- **Regulasi:** ringkasan aturan mengikuti materi sumber per Mei 2026. Aturan sering berubah — selalu verifikasi langsung ke otoritas resmi sebelum terbang. Menurut materi, terbang di luar jarak pandang (BVLOS) untuk rekreasi tidak diperbolehkan tanpa otorisasi.
- **Lab Link** memakai model perambatan sederhana yang disetel ke kisaran tabel estimasi cheat sheet. Angka pastinya berbeda dari aturan praktis di materi; yang sama adalah arah pengaruhnya. Bukan pengganti bench test dan range test.
- **Lab Baterai** menganggap cruise 60 km/jam terhadap udara dengan konsumsi tetap; belum menghitung sag, tanjakan dan gaya terbang. Ukur mAh per km quad-mu sendiri.
- Cerita, karakter dan lokasi SkyFlux adalah fiksi. Ilustrasi dibuat dengan bantuan AI.
- Nama produk dan firmware disebut hanya untuk merujuk hal yang dibahas; proyek komunitas ini tidak berafiliasi dengan pihak-pihak tersebut.

Komik SkyFlux lainnya: [Terbang Halus, Arka! (PID & Rate Betaflight)](https://edhotp.github.io/Belajar-Betaflight-PID-Rate/)
