# Kelas AI Muar — Sales Page

Source code sales page **Kelas AI & Digital Marketing** (kelas fizikal sehari di Muar, 31 Okt 2026).

Satu fail HTML sahaja: HTML + CSS + sedikit JavaScript, tiada build step, tiada framework.
Ikon dan ilustrasi ialah SVG 3D yang ditulis terus dalam `index.html`.

## Buka

Buka `index.html` terus dalam browser, atau jalankan server kecil:

```sh
python3 -m http.server 8000
# buka http://localhost:8000
```

## Isi

```
index.html   page penuh (19 seksyen: hero, masalah, solusi, demo, silibus, BTS, trainer, offer, pricing, FAQ, CTA)
img/         gambar WebP + 1 video BTS (MP4)
```

## Nota

- Harga ikut tarikh Malaysia (skrip pricing di hujung `index.html`). Kelas dah berlangsung,
  jadi butang tiket disembunyikan selepas 31 Okt 2026. Tukar tarikh dalam skrip itu untuk guna semula.
- Butang tiket guna `?add-to-cart=<id>` untuk checkout kedai. Ganti dengan link checkout anda sendiri.
- Gambar, video dan teks ialah milik Goldmines Marketing. Guna kod sebagai rujukan, bukan isi kandungannya.
