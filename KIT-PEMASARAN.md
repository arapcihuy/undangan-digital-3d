# KIT PEMASARAN — Undangan Digital 3D Sinematik (Rangga Studio)

## 1. SKEMA HARGA & MARGIN
| Paket | Harga | Estimasi kerja | Margin |
|---|---|---|---|
| Basic (2D) | Rp 99rb | 1 jam (clone sample-03, ganti konten) | ~95% |
| Premium (2D+musik) | Rp 199rb | 1,5 jam (clone sample-03 + musik) | ~95% |
| Signature 3D (WebGL) | Rp 499rb | 2-3 jam (clone sample-05, ganti foto/konten) | ~90% |

Kunci margin: produk SUDAH jadi (sample-03 & sample-05). Tiap pesanan = clone folder + ganti
foto/teks/nama/rekening/hosting. Bukan bikin dari nol.
Target realistis bulan 1: 10-15 order (2 Basic + 5 Premium + 3 Signature ≈ Rp 2,9-3,7 jt).

## 2. SISTEM ORDER (siap pakai)
- WA utama: 6281387906930 (GANTI dgn nomor asli di landing.html — 6 kemunculan)
- Alur: chat → kirim nama/tanggal/foto → DP 50% → kerjakan (clone) → review → link final
- File kerja: tiap order = folder baru `orders/<nama>/` clone dari sample, ganti assets + data
- Hosting gratis: Cloudflare Pages (drag&drop folder) atau Tinaa/Netlify. Domain gratis *.pages.dev
- Nama tamu otomatis: link sebar pakai `?to=Nama%20Tamu` (bisa dibuatkan daftar via spreadsheet)

## 3. KONTEN IG (siap posting)
Post 1 ( carousel 3 slide )
  Slide1: "Undangan yang bikin tamu nahan napas." + foto cover
  Slide2: video/record demo buka segel → ledakan cahaya
  Slide3: "Harga mulai 99rb, jadi 24 jam. Demo di bio."
  Caption:
  Kamu sudah bayar fotografer jutaan, tapi undangannya template klik-klik biasa?
  Undangan digital 3D sinematik: segel lilin emas, partikel bercahaya, foto kalian jadi cover sinematik.
  Tamu buka, langsung diam, lalu share ke story. Itu hype sebelum hari H.
  Mulai Rp 99rb. Jadi 1x24 jam. Revisi sampai puas.
  DM "DEMO" untuk lihat sendiri. Slot minggu ini tinggal 3.

Post 2 ( foto sebelum-sesudah )
  Caption: Template pasaran: 5 detik, tutup, lupa.
  Ini: tamu mainkan cahayanya, dengar musiknya, baca cerita kalian sampai habis.
  Bedanya 99rb. Serius.

Story ( 3 frame, tiap hari )
  F1: teks besar "PENGANTIN 2027, JANGAN PAKAI TEMPLATE BIASA" + poll [Alasan / Kasih demo]
  F2: record layar demo 10 detik (buka segel)
  F3: "Slot minggu ini: 3. DM 'DEMO'."

## 4. SKRIP TIKTOK/REELS (3 video, tanpa perlu muka)
V1 (hook visual, 12 dtk): record layar: scroll feed biasa (template bosenin) → CUT → buka demo 3D
  (segel → ledakan cahaya). Teks: "Undangan pengantin temenku vs undangan KAMU."
V2 ( POV, 15 dtk ): "POV: kamu kirim link undangan ke grup keluarga" → record tamu2 respon
  (pakai teks imajiner) → CTA "harga di komentar"
V3 ( nilai jual, 20 dtk ): talking-less: "3 alasan undangan digital 3D sekarang lagi naik daun:
  1) tamu share ke story = promosi gratis, 2) RSVP tercatat rapi, 3) amplop digital QRIS —
  uang langsung masuk sebelum hari H." → CTA.
  Musik: trending ambient. Posting jam 19-21. Hashtag: #undangandigital #undanganpernikahan
  #pengantin2027 #weddinginspiration #undanganmurah

## 5. TEMPLAT BALAS DM (salin-tempel)
DM masuk "pm harga":
  "Halo kak, ada 3 paket: Basic 99rb / Premium 199rb / Signature 3D 499rb (yang 3D sinematik,
  bisa dilihat demo dulu). Mau kirim link demonya? Kalau cocok tinggal kirim
  nama kalian, tanggal acara, dan foto-foto. Jadi 1x24 jam setelah DP."
Follow-up (24 jam, belum DP):
  "Kak, slot pengerjaan minggu ini masih 2. Kalau mau amanin tanggalnya, cukup DP 50% dulu,
  sisanya setelah draf disetujui. Biasanya minggu-minggu dekat hari H antrian lagi."
Objection "kok mahal":
  "Di yogyakarta/jakarta undangan premium kertas aja 500rb-1jt per box kak, itu tidak bisa
  dikirim ke 200 tamu sekaligus. Yang ini satu link aktif sampai hari H+30, ada RSVP +
  amplop QRIS — jadi hadiah uang langsung masuk, tanpa antre di reception."

## 6. KANAL AKUISISI (urutan prioritas)
1. Grup FB "PPDI/undangan pernikahan/mempelai 2027" — jawab pertanyaan organik + demo link (GRATIS)
2. TikTok organic (3 video/minggu) — hook visual demo
3. Instagram story + carousel — share demo + slot counter
4. KOMUNITAS pengantin (binis virtual, KUA online) — tawarkan kemitraan TO penghenna day
5. Market deps: coba listing di marketplace jasa (bikin gig "jasa undangan digital 3D")

## 7. CHECKLIST SEBELUM JUALAN
- [x] Nomor WA 6281387906930 terpasang di landing (6 CTA)
- [x] HOSTING AKTIF: https://undangan-3d.pages.dev (landing) · /demo (undangan 3D)
      Re-deploy setelah edit: `cd ~/undangan-digital && wrangler pages deploy dist-deploy --project-name=undangan-3d --branch=main`
- [ ] Ganti QRIS png dgn QRIS asli (kalau dipakai di demo ke customer)
- [ ] Siapkan folder template kerja: orders/template/ (SUDAH: orders/template-2d & template-3d)
- [ ] Catat tiap order di spreadsheet: nama, paket, tanggal nikah, DP, link final, deadline

## 8. TEMPLATE SLACK/SPREADSHEET ORDER
Kolom: Tanggal | Nama client | WA | Paket | Harga | DP | Status kerja | Link demo | Link final | Deadline | Catatan
Status kerja: masuk → DP → draf → revisi → final → kirim → SELESAI