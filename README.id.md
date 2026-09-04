<div align="center">

🌐 **Bahasa:** 🇬🇧 [English](README.md) | 🇮🇩 Bahasa Indonesia | [🇸🇦 العربية](README.ar.md) | [🇨🇳 中文](README.zh.md) | [🇪🇸 Español](README.es.md) | [🇧🇷 Português](README.pt.md)

# 🎬 DramaBox Source API — Source Code Lengkap

**API konten DramaBox self-hosted — katalog, pencarian, episode & video siap putar, tanpa VIP.**

**Beli sekali, hosting selamanya. Source TypeScript lengkap, tanpa biaya lisensi, tanpa dependensi tersembunyi.**

**DramaBox streaming API** self-hosted — integrasi API resmi untuk drama pendek: cari katalog, ambil daftar episode, dan streaming video MP4 langsung dengan semua episode terbuka.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Coba_Sekarang-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![API Key Gratis](https://img.shields.io/badge/API_Key_Gratis-Bot_Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 Coba Dulu Sebelum Beli

- **Konsol docs live:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **API key gratis:** https://t.me/dramaboxplusbot — ambil key dan langsung uji semua endpoint.

Yang berjalan di demo adalah kode yang persis sama.

---

## 💰 Apa yang Kamu Beli

**Layanan TypeScript teruji produksi** yang berkomunikasi langsung dengan backend DramaBox — tanpa perantara antara kamu dan sumbernya.

- **Tanpa VIP — guest buka semua** — terverifikasi 2026-09-04, setiap episode rilis mengembalikan MP4 playable.
- **Tanpa API pihak ketiga** — tidak ada yang bisa mem-ban, menaikkan harga, atau hilang.
- **Tanpa biaya per-request** — satu-satunya biaya adalah VPS-mu.
- **Siap dijual kembali / white-label** — server, key, dan harga kamu sendiri.

---

## ✨ Fitur Utama

- 🔓 **Semua episode terbuka tanpa VIP** — MP4 langsung bisa diputar, tanpa file terenkripsi
- 📡 **24+ endpoint** — feeds, pencarian, genre, ranking, detail, episode, batch download
- 🌍 **15 bahasa** via `?lang=` — termasuk Indonesia, Inggris, Mandarin, Arab, Spanyol (terverifikasi 15/15)
- ⚡ **Caching pintar** — TTL berlapis + snapshot disk, restart tidak memperlambat
- 🛡️ **Transport anti-WAF** — profil TLS mobile + request tertanda tangan + rotasi sesi otomatis
- 🔄 **Rotasi proxy** — proxy statis atau pool gratis yang otomatis refresh
- 🔑 **Sistem API key** — tier, rate limit, kuota harian
- 🔌 **Monitor penggunaan live** — stream WebSocket per key

---


## 🔓 Full Unlock — Tanpa VIP (terverifikasi 2026-09-04)

> **Update 2026-09-04:** Tanpa akun VIP. Sesi guest membuka **100% episode rilis** termasuk berbayar — terverifikasi live lintas 23 drama dan 15 bahasa (`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`). Contoh `41000118399` → 82/82 dengan 70 charged playable. `served < chapterCount` artinya belum rilis (normal untuk drama ongoing), bukan terkunci.

**Verifikasi:**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=in" -H "X-API-Key: test"
curl "localhost:3012/api/stream?id=41000118399&ep=81&lang=in" -H "X-API-Key: test"
```

---
## ⚡ Mulai Cepat

```bash
npm install
cp .env.example .env    # sesuaikan
npm run build && npm start
```

Kebutuhan: Node.js ≥ 18, VPS Linux apa pun (RAM 512 MB cukup).

---

## 🗂️ Source Services Lainnya

| freereels | melolo | moboreels | goodshort |
|---|---|
| [Tanpa paywall](https://github.com/beranalpa/FreeReels-API-Free) | [Dekripsi DRM](https://github.com/beranalpa/Melolo-API-Free) | [Full unlock](https://github.com/beranalpa/MoboReels-API-Free) | [Ad-unlock 1080p](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 Dukungan

- API key gratis & pertanyaan: [@dramaboxplusbot](https://t.me/dramaboxplusbot)
- Konsol live: https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**Source code lengkap. Self-hosted. Siap dijual kembali. API-mu, aturanmu.**

</div>
