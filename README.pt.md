<div align="center">

🌐 **Idioma:** [🇬🇧 English](README.md) | [🇮🇩 Bahasa Indonesia](README.id.md) | [🇸🇦 العربية](README.ar.md) | [🇨🇳 中文](README.zh.md) | [🇪🇸 Español](README.es.md) | 🇧🇷 Português

# 🎬 DramaBox Source API — Código-Fonte Completo

**API de conteúdo DramaBox auto-hospedada — catálogo, busca, episódios e vídeo direto, sem VIP.**

**Compre uma vez, hospede para sempre. Código TypeScript completo, sem taxas de licença, sem dependências ocultas.**

**API de streaming DramaBox** auto-hospedada — integração com a API oficial para dramas curtos: busque no catálogo, obtenha listas de episódios e reproduza vídeo MP4 direto com todos os episódios desbloqueados.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Experimente_Agora-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![API Key Grátis](https://img.shields.io/badge/API_Key_Grátis-Bot_Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 Teste Antes de Comprar

- **Console de docs ao vivo:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **API key grátis:** https://t.me/dramaboxplusbot — pegue uma key e teste cada endpoint na hora.

O que roda na demo é exatamente este código.

---

## 💰 O Que Você Está Comprando

Um **serviço TypeScript testado em produção** que fala direto com o backend da DramaBox — sem intermediários entre você e a fonte.

- **Sem VIP — guest desbloqueia tudo** — verificado 2026-09-04, cada episódio publicado retorna MP4 reproduzível.
- **Sem API de terceiros** — ninguém pode banir você, aumentar preços ou sumir.
- **Sem custo por requisição** — seu único custo é o seu VPS.
- **Pronto para revender / white-label** — seu servidor, suas keys, seus preços.

---

## ✨ Recursos Principais

- 🔓 **Todos os episódios sem VIP** — MP4 direto reproduzível, sem arquivos criptografados
- 📡 **24+ endpoints** — feeds, busca, gêneros, rankings, detalhes, episódios, download em lote
- 🌍 **15 idiomas** via `?lang=` — inclui indonésio, inglês, chinês, árabe, espanhol (verificado 15/15)
- ⚡ **Cache inteligente** — TTL em camadas + snapshot em disco, reinícios não atrasam você
- 🛡️ **Transporte anti-WAF** — perfil TLS móvel + requisições assinadas + rotação automática de sessões
- 🔄 **Rotação de proxies** — proxies estáticos ou pool grátis auto-atualizável
- 🔑 **Sistema de API keys** — tiers, rate limits, cotas diárias
- 🔌 **Monitor de uso ao vivo** — fluxo WebSocket por key

---


## 🔓 Desbloqueio Total — Sem VIP (verificado 2026-09-04)

> **Atualização 2026-09-04:** Sem VIP. Sessões guest desbloqueiam **100% publicados** incluindo pagos — verificado em 23 dramas e 15 idiomas (`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`). Exemplo `41000118399` → 82/82 com 70 pagos reproduzíveis. `served < chapterCount` é não publicado (normal), não bloqueado.

**Verificar:**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=pt" -H "X-API-Key: test"
```

---
## ⚡ Início Rápido

```bash
npm install
cp .env.example .env    # ajuste
npm run build && npm start
```

Requisitos: Node.js ≥ 18, qualquer VPS Linux (512 MB de RAM é suficiente).

---

## 🗂️ Mais Serviços Fonte

| freereels | melolo | moboreels | goodshort |
|---|---|
| [Sem paywall](https://github.com/beranalpa/FreeReels-API-Free) | [Descriptografia DRM](https://github.com/beranalpa/Melolo-API-Free) | [Desbloqueio total](https://github.com/beranalpa/MoboReels-API-Free) | [1080p por anúncios](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 Suporte

- API key grátis e dúvidas: [@dramaboxplusbot](https://t.me/dramaboxplusbot)
- Console ao vivo: https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**Código-fonte completo. Auto-hospedado. Pronto para revender. Sua API, suas regras.**

</div>
