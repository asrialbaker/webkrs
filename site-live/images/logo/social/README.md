# Logotaip media sosial — footer

Letakkan 5 fail SVG ini dalam folder ini. Nama fail mesti tepat (huruf kecil):

Semua lima logotaip sudah siap dipasang.

| Fail             | Platform  | Saiz    |
|------------------|-----------|---------|
| `facebook.png`   | Facebook  | 532×96  |
| `instagram.png`  | Instagram | 338×96  |
| `tiktok.png`     | TikTok    | 359×96  |
| `youtube.png`    | YouTube   | 423×96  |
| `whatsapp.png`   | WhatsApp  | 414×96  |

Semua fail diproses sama: latar dipotong lut sinar, artwork ditukar putih
tulen, dipangkas rapat, tinggi 96px (4× saiz paparan 23px untuk skrin retina).
Bahagian dalam yang "dikorek" (contoh: segi tiga main YouTube, gagang telefon
WhatsApp) kekal lut sinar supaya warna footer menembusinya.

Fail lama `youtube.svg` (ikon sahaja) sudah tidak digunakan — boleh dipadam.

## Menggantikan mana-mana logo

Hantar fail asal (PNG/SVG/JPG, latar apa-apa warna) dan ia akan diproses
mengikut resipi yang sama supaya konsisten dengan yang lain.

Sumber rasmi jika perlu versi terkini:

- Facebook · https://about.meta.com/brand/resources/facebook/logo/
- Instagram · https://about.meta.com/brand/resources/instagram/
- TikTok · https://www.tiktok.com/about/brand-guidelines
- YouTube · https://www.youtube.com/howyoutubeworks/resources/brand-resources/
- WhatsApp · https://about.meta.com/brand/resources/whatsapp/whatsapp-brand/

## Spesifikasi

- **Format:** SVG (bukan PNG). Fail asal dari halaman brand di atas sudah SVG.
- **Jenis:** guna versi **logotaip penuh** (ikon + nama jenama), bukan ikon sahaja —
  contoh: lambang "f" + perkataan "facebook".
- **Warna:** pilih versi **satu-warna / putih** jika ada.
  CSS footer sudah memaksa artwork jadi putih (`filter:brightness(0) invert(1)`),
  jadi versi berwarna pun akan jadi putih — tetapi versi satu-warna hasilnya lebih kemas.
- **Saiz:** tak perlu diubah. CSS menetapkan tinggi 23px, lebar auto.
  Pastikan SVG ada atribut `viewBox` supaya nisbahnya kekal betul.
- **Jangan** ubah bentuk, jarak huruf atau nisbah logo — ikut garis panduan jenama.

## Sebelum fail dimuat naik

Footer akan memaparkan teks alt ("Facebook", "Instagram", …) menggantikan
imej yang belum ada. Laman tidak rosak, cuma belum menunjukkan logotaip.

## Selepas dimuat naik

Salin fail yang sama ke **kedua-dua** folder:

- `site-live/images/logo/social/`
- `site-demo/images/logo/social/`
