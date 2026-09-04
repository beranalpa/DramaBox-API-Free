<div align="center">

🌐 **Language:** 🇬🇧 English | [🇮🇩 Bahasa Indonesia](README.id.md) | [🇸🇦 العربية](README.ar.md) | [🇨🇳 中文](README.zh.md) | [🇪🇸 Español](README.es.md) | [🇧🇷 Português](README.pt.md)

# 🎬 DramaBox Source API — Full Source Code

**Self-hosted DramaBox content API — catalog, search, episodes & direct playable video, no VIP needed.**

**Buy once, host forever. Full TypeScript source, no license fees, no hidden dependencies.**

Self-hosted **DramaBox streaming API** — official API integration for short dramas: search the catalog, get episode lists, and stream direct MP4 video with all episodes unlocked.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Try_It_Now-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![Free API Key](https://img.shields.io/badge/Free_API_Key-Telegram_Bot-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 Try Before You Buy

- **Live docs console:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **Free API key:** https://t.me/dramaboxplusbot — grab a key and test every endpoint instantly.

What runs on the demo is exactly this code.

---

## 💰 What You're Buying

A **production-tested TypeScript service** that talks directly to the DramaBox backend — no middleman between you and the source.

- **No VIP needed — guest unlocks all** — verified 2026-09-04, every released episode returns playable MP4.
- **No third-party API** — nothing can ban you, raise prices, or disappear.
- **No per-request fees** — your only cost is your VPS.
- **Resell / white-label ready** — your server, your keys, your pricing.

---

## ✨ Key Features

- 🔓 **All episodes unlocked without VIP** — direct playable MP4, no encrypted files
- 📡 **24+ endpoints** — feeds, search, genres, rankings, detail, episodes, batch download
- 🌍 **15 languages** via `?lang=` — including Indonesian, English, Chinese, Arabic, Spanish (verified 15/15)
- ⚡ **Smart caching** — layered TTL + disk snapshot, restarts never slow you down
- 🛡️ **Anti-WAF transport** — mobile TLS profile + signed requests + auto session rotation
- 🔄 **Proxy rotation** — static proxies or free auto-refreshing pool
- 🔑 **API key system** — tiers, rate limits, daily quotas
- 🔌 **Live usage monitor** — WebSocket stream per key

---


## 🔓 Full Unlock — No VIP Needed (verified 2026-09-04)

> **Update 2026-09-04:** No VIP account needed. Guest sessions unlock **100% of released episodes** including paid/charged — verified live across 23 dramas and 15 languages (`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`). Example `41000118399` → 82/82 with 70 charged playable. `served < chapterCount` means unreleased (normal for ongoing series), not locked.

**Verify:**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=in" -H "X-API-Key: test"
curl "localhost:3012/api/stream?id=41000118399&ep=81&lang=en" -H "X-API-Key: test"
```

---
## ⚡ Quick Start

```bash
npm install
cp .env.example .env    # adjust
npm run build && npm start
```

Requirements: Node.js ≥ 18, any Linux VPS (512 MB RAM is plenty).

---

## 🗂️ More Source Services

| freereels | melolo | moboreels | goodshort |
|---|---|
| [Zero paywall](https://github.com/beranalpa/FreeReels-API-Free) | [DRM decrypt](https://github.com/beranalpa/Melolo-API-Free) | [Full unlock](https://github.com/beranalpa/MoboReels-API-Free) | [1080p ad-unlock](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 Support

- Free API key & questions: [@dramaboxplusbot](https://t.me/dramaboxplusbot)
- Live console: https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**Full source code. Self-hosted. Resell-ready. Your API, your rules.**

</div>
