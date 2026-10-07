# Undangan Pernikahan Digital 3D Sinematik

Undangan pernikahan digital dengan WebGL/Three.js — partikel emas bercahaya, bloom sinematik,
segel lilin interaktif, dan foto pasangan sebagai bintang utama. Nada desainnya editorial:
hitam, emas, serif klasik. Tanpa kartun, tanpa template klik-klik biasa.

**Lihat langsung (live):**
- Landing + harga: https://undangan-3d.pages.dev
- Demo undangan 3D: https://undangan-3d.pages.dev/demo/?to=Nama%20Tamu
  (ganti `to=` dengan nama tamu — setiap tamu melihat namanya sendiri di cover)

## Struktur
```
site/                  -> landing page + demo 3D (yang di-deploy ke Cloudflare Pages)
template-2d-elegan/    -> versi 2D (tanpa WebGL), muat lebih cepat di HP lama
KIT-PEMASARAN.md       -> skema harga, konten IG/TikTok, templat DM, alur order
```

## Fitur
- Pembuka sinematik: segel lilin emas, nama muncul huruf per huruf, ledakan kunang-kunang
- Medan partikel WebGL + Unreal Bloom (cahaya nyata, bukan gambar)
- Kamera parallax mengikuti gerak mouse/touch, kamera menyusuri partikel saat scroll
- 13 seksi: profil mempelai, cerita, acara, galeri geser + lightbox, video,
  dress code, rundown, live stream, amplop digital (BCA/Mandiri/QRIS), RSVP + buku tamu
- Nama tamu otomatis via `?to=Nama`, countdown, musik latar
- Fallback otomatis: kalau WebGL tak tersedia, tampil versi gradient yang tetap elegan
- Versi ringan otomatis untuk HP kentang

## Teknologi
HTML + CSS + vanilla JS, Three.js r160 (ES module), UnrealBloomPass,
font Playfair Display / Cormorant Garamond / Jost. Tanpa framework, tanpa build step.

## Pakai untuk klien sendiri
1. Clone repo, copy folder `site/demo/`, ganti `assets/` dengan foto klien
2. Edit teks/nama/rekening di `index.html`
3. Deploy ke Cloudflare Pages (drag & drop) — selesai

## Kontak & pemesanan
WhatsApp: 081387906930 — paket mulai Rp 99rb, jadi 1x24 jam.

---
Lisensi kode: silakan dipakai/dimodifikasi untuk proyek pribadi mausupun klien.
Foto pada demo: Unsplash (lisensi bebas, kredit tidak diwajibkan).
