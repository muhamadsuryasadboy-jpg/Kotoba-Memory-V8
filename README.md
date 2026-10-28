# Kotoba Memory

Aplikasi hafalan kotoba bahasa Jepang. Jalan offline, tanpa akun, semua data tersimpan di HP.
Kamu menempel daftar kotoba sendiri, lalu app mengatur jadwal ulangnya.

## Tampilan

| Layar awal | Menu belajar | Kenali 5 kata | Jawaban |
|---|---|---|---|
| <img src="screenshots/layar-awal.jpg" width="200"> | <img src="screenshots/menu-belajar.jpg" width="200"> | <img src="screenshots/kenali-kata.jpg" width="200"> | <img src="screenshots/jawaban.jpg" width="200"> |

Catatan: kata di tangkapan layar hanyalah contoh.

## Fitur utama
- **Paket 5 kata baru**: kenali 5 kata, lalu dites berulang sampai kamu menekan "Aku hafal". Target kata baru per hari bisa diatur (mis. 50).
- **Atur per bab**: kata diambil urut per bab. Hari terakhir sebuah bab jadi pas (mis. bab 77 kata = 50 + 27).
- **Review otomatis**: tiap kata yang dipelajari masuk jadwal ulang (besok, beberapa hari lagi, dst).
- **Kata sulit**: ditandai manual atau terdeteksi (sering lupa), bisa dibagi grup, Mode Fokus, dan Review kebut untuk semua kata yang sudah kuat.
- **Petunjuk dan tebak ketik**: bantu mengingat tanpa langsung membuka jawaban.
- **Catatan jembatan keledai**, statistik, kuis, backup dan pulihkan.

## Cara membuat APK (dari HP)
1. Repo berisi: `index.html`, `package.json`, `capacitor.config.json`, `icon-only.png`, `icon-foreground.png`, `icon-background.png`, `splash.png`, `splash-dark.png`, `.gitignore`, `README.md`, folder `screenshots`, dan `.github/workflows/main.yml`.
2. Nama berkas HTML harus tepat `index.html`.
3. Buka tab **Actions**, tunggu hijau (sekitar 5-8 menit), lalu unduh `KotobaMemory-apk` dari Artifacts.

## Pindah data dari app lama
Setelan, Backup, Buat backup, Salin. Di app baru: Setelan, Backup, tempel, Pulihkan.

## Batasan
- Skor kata dan pemeriksa jawaban ketik adalah perkiraan, bukan jaminan (skor maksimal 95).
- Arti dan bacaan berasal dari daftar yang kamu tempel sendiri.
- APK debug untuk pemakaian pribadi.
