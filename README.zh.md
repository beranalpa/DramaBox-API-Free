<div align="center">

🌐 **语言:** [🇬🇧 English](README.md) | [🇮🇩 Bahasa Indonesia](README.id.md) | [🇸🇦 العربية](README.ar.md) | 🇨🇳 中文 | [🇪🇸 Español](README.es.md) | [🇧🇷 Português](README.pt.md)

# 🎬 DramaBox Source API — 完整源代码

**自托管 DramaBox 内容 API — 目录、搜索、剧集与直连视频，无需 VIP。**

**一次购买，永久托管。完整 TypeScript 源码，无许可费，无隐藏依赖。**

自托管 **DramaBox 流媒体 API** — 官方 API 集成，专为短剧打造：搜索目录、获取剧集列表、直接播放 MP4 视频，全部剧集解锁。

[![在线演示](https://img.shields.io/badge/Live_Demo-立即体验-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![免费 API Key](https://img.shields.io/badge/Free_API_Key-Telegram_Bot-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 先试后买

- **在线文档控制台:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **免费 API Key:** https://t.me/dramaboxplusbot — 领取 key，立刻测试所有端点。

演示上运行的，就是这套代码。

---

## 💰 你买到的是什么

一套**经过生产验证的 TypeScript 服务**，直连 DramaBox 后端——你与源头之间没有中间商。

- **无需 VIP — 游客全解锁** — 2026-09-04 验证，所有已发布剧集返回可播放 MP4。
- **不依赖第三方 API** — 没有人能封禁你、涨价或消失。
- **零按次费用** — 唯一成本是你的 VPS。
- **可转售 / 白标** — 你的服务器、你的 key、你的定价。

---

## ✨ 核心功能

- 🔓 **无需 VIP 全解锁** — 直连可播放 MP4，无加密文件
- 📡 **24+ 端点** — 信息流、搜索、分类、排行榜、详情、剧集、批量下载
- 🌍 **15 种语言** 通过 `?lang=` — 含印尼语、英语、中文、阿拉伯语、西班牙语（已验证 15/15）
- ⚡ **智能缓存** — 分层 TTL + 磁盘快照，重启不拖慢速度
- 🛡️ **防 WAF 传输** — 移动端 TLS 指纹 + 签名请求 + 自动会话轮换
- 🔄 **代理轮换** — 静态代理或自动刷新的免费代理池
- 🔑 **API Key 系统** — 套餐分级、速率限制、每日配额
- 🔌 **实时用量监控** — 每个 key 的 WebSocket 流

---


## 🔓 完整解锁 — 无需 VIP（2026-09-04 已验证）

> **更新 2026-09-04：** 无需 VIP。游客解锁**所有已发布 100% 剧集**（含付费）—— 现网跨 23 部剧、15 种语言验证（`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`）。示例 `41000118399` → 82/82，70 集付费均可播放。`served < chapterCount` 为未发布（连载正常），非锁定。

**验证：**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=zh" -H "X-API-Key: test"
```

---
## ⚡ 快速开始

```bash
npm install
cp .env.example .env    # 按需调整
npm run build && npm start
```

要求：Node.js ≥ 18，任意 Linux VPS（512 MB 内存即可）。

---

## 🗂️ 更多源服务

| freereels | melolo | moboreels | goodshort |
|---|---|
| [零付费墙](https://github.com/beranalpa/FreeReels-API-Free) | [DRM 解密](https://github.com/beranalpa/Melolo-API-Free) | [全解锁](https://github.com/beranalpa/MoboReels-API-Free) | [1080p 广告解锁](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 支持

- 免费 API Key 与咨询：[@dramaboxplusbot](https://t.me/dramaboxplusbot)
- 在线控制台：https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**完整源代码。自托管。可转售。你的 API，你的规则。**

</div>
