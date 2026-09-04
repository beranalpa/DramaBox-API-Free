<div align="center">

🌐 **Idioma:** [🇬🇧 English](README.md) | [🇮🇩 Bahasa Indonesia](README.id.md) | [🇸🇦 العربية](README.ar.md) | [🇨🇳 中文](README.zh.md) | 🇪🇸 Español | [🇧🇷 Português](README.pt.md)

# 🎬 DramaBox Source API — Código Fuente Completo

**API de contenido DramaBox autoalojada — catálogo, búsqueda, episodios y video directo, sin VIP.**

**Compra una vez, aloja para siempre. Código TypeScript completo, sin tarifas de licencia, sin dependencias ocultas.**

**API de streaming DramaBox** autoalojada — integración con la API oficial para dramas cortos: busca en el catálogo, obtén listas de episodios y reproduce video MP4 directo con todos los episodios desbloqueados.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Pruébalo_Ahora-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![API Key Gratis](https://img.shields.io/badge/API_Key_Gratis-Bot_Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 Prueba Antes de Comprar

- **Consola de docs en vivo:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **API key gratis:** https://t.me/dramaboxplusbot — toma una key y prueba cada endpoint al instante.

Lo que corre en la demo es exactamente este código.

---

## 💰 Qué Estás Comprando

Un **servicio TypeScript probado en producción** que habla directo con el backend de DramaBox — sin intermediarios entre tú y la fuente.

- **Sin VIP — invitado desbloquea todo** — verificado 2026-09-04, cada episodio publicado devuelve MP4 reproducible.
- **Sin API de terceros** — nadie puede banearte, subir precios o desaparecer.
- **Sin costo por petición** — tu único costo es tu VPS.
- **Listo para revender / white-label** — tu servidor, tus keys, tus precios.

---

## ✨ Características Clave

- 🔓 **Todos los episodios sin VIP** — MP4 directo reproducible, sin archivos cifrados
- 📡 **24+ endpoints** — feeds, búsqueda, géneros, rankings, detalle, episodios, descarga por lotes
- 🌍 **15 idiomas** vía `?lang=` — incluye indonesio, inglés, chino, árabe, español (verificado 15/15)
- ⚡ **Caché inteligente** — TTL en capas + snapshot en disco, los reinicios no te frenan
- 🛡️ **Transporte anti-WAF** — perfil TLS móvil + peticiones firmadas + rotación automática de sesiones
- 🔄 **Rotación de proxies** — proxies estáticos o pool gratis auto-refrescante
- 🔑 **Sistema de API keys** — tiers, rate limits, cuotas diarias
- 🔌 **Monitor de uso en vivo** — flujo WebSocket por key

---


## 🔓 Desbloqueo Total — Sin VIP (verificado 2026-09-04)

> **Actualización 2026-09-04:** Sin VIP. Sesiones guest desbloquean **100% publicados** incluido de pago — verificado en 23 dramas y 15 idiomas (`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`). Ejemplo `41000118399` → 82/82 con 70 de pago reproducibles. `served < chapterCount` es no publicado (normal), no bloqueado.

**Verificar:**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=es" -H "X-API-Key: test"
```

---
## ⚡ Inicio Rápido

```bash
npm install
cp .env.example .env    # ajusta
npm run build && npm start
```

Requisitos: Node.js ≥ 18, cualquier VPS Linux (512 MB de RAM es suficiente).

---

## 🗂️ Más Servicios Fuente

| freereels | melolo | moboreels | goodshort |
|---|---|
| [Sin paywall](https://github.com/beranalpa/FreeReels-API-Free) | [Descifrado DRM](https://github.com/beranalpa/Melolo-API-Free) | [Desbloqueo total](https://github.com/beranalpa/MoboReels-API-Free) | [1080p por anuncios](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 Soporte

- API key gratis y consultas: [@dramaboxplusbot](https://t.me/dramaboxplusbot)
- Consola en vivo: https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**Código fuente completo. Autoalojado. Listo para revender. Tu API, tus reglas.**

</div>
