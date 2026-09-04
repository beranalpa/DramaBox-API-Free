<div align="center">

🌐 **اللغة:** [🇬🇧 English](README.md) | [🇮🇩 Bahasa Indonesia](README.id.md) | 🇸🇦 العربية | [🇨🇳 中文](README.zh.md) | [🇪🇸 Español](README.es.md) | [🇧🇷 Português](README.pt.md)

# 🎬 DramaBox Source API — كود المصدر الكامل

**واجهة ذاتية الاستضافة لمحتوى DramaBox — كتالوج، بحث، حلقات وفيديو مباشر، بدون VIP.**

**اشترِ مرة واحدة، واستضف إلى الأبد. كود TypeScript كامل، بدون رسوم ترخيص، بدون تبعيات خفية.**

واجهة **DramaBox streaming API** ذاتية الاستضافة — تكامل مع الواجهة الرسمية للدراما القصيرة: ابحث في الكتالوج، احصل على قوائم الحلقات، وشغّل فيديو MP4 مباشرًا مع فتح جميع الحلقات.

[![Live Demo](https://img.shields.io/badge/Live_Demo-جرّب_الآن-green?style=for-the-badge)](https://api-pro.hoshiyomi.my.id/docs/dramabox)
[![API Key مجاني](https://img.shields.io/badge/API_Key_مجاني-Bot_Telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/dramaboxplusbot)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org)

</div>

---

## 🚀 جرّب قبل الشراء

- **كونسول التوثيق المباشر:** https://api-pro.hoshiyomi.my.id/docs/dramabox
- **مفتاح API مجاني:** https://t.me/dramaboxplusbot — خذ المفتاح وجرّب كل نقاط النهاية فورًا.

ما يعمل على النسخة التجريبية هو هذا الكود نفسه.

---

## 💰 ماذا تشتري؟

**خدمة TypeScript مُختبَرة في الإنتاج** تتواصل مباشرة مع خوادم DramaBox — بدون وسيط بينك وبين المصدر.

- **بدون VIP — الضيف يفتح الكل** — تم التحقق 2026-09-04، كل حلقة منشورة تُرجع MP4 قابل للتشغيل.
- **بدون واجهة طرف ثالث** — لا أحد يستطيع حظرك أو رفع الأسعار أو الاختفاء.
- **بدون رسوم لكل طلب** — تكلفتك الوحيدة هي خادمك.
- **جاهز لإعادة البيع / العلامة البيضاء** — خادمك، مفاتيحك، أسعارك.

---

## ✨ الميزات الرئيسية

- 🔓 **جميع الحلقات بدون VIP** — MP4 مباشر قابل للتشغيل، بدون ملفات مشفرة
- 📡 **أكثر من 24 نقطة نهاية** — خلاصات، بحث، أنواع، تصنيفات، تفاصيل، حلقات، تحميل دفعة
- 🌍 **15 لغة** عبر `?lang=` — تشمل الإندونيسية، الإنجليزية، الصينية، العربية، الإسبانية (تم التحقق 15/15)
- ⚡ **كاش ذكي** — TTL متعدد الطبقات + لقطة قرص، إعادة التشغيل لا تبطئك
- 🛡️ **نقل مضاد للحماية** — ملف TLS للجوال + طلبات موقعة + تناوب تلقائي للجلسات
- 🔄 **تناوب البروكسي** — بروكسيات ثابتة أو تجمع مجاني يتحدث تلقائيًا
- 🔑 **نظام مفاتيح API** — فئات، حدود معدل، حصص يومية
- 🔌 **مراقبة الاستخدام لحظيًا** — بث WebSocket لكل مفتاح

---


## 🔓 فتح كامل — بدون VIP (تم التحقق 2026-09-04)

> **تحديث 2026-09-04:** بدون VIP. جلسات الضيف تفتح **100% المنشورة** حتى المدفوعة — تم التحقق عبر 23 دراما و 15 لغة (`in, en, id, zh, zh-Hans, zh-Hant, es, pt, ar, fr, de, ja, ko, th, vi`). مثال `41000118399` → 82/82 مع 70 مدفوعة قابلة للتشغيل. `served < chapterCount` يعني غير منشورة (طبيعي)، ليست مقفلة.

**تحقق:**
```bash
curl "localhost:3012/api/chapters/all?id=41000118399&lang=ar" -H "X-API-Key: test"
```

---
## ⚡ البدء السريع

```bash
npm install
cp .env.example .env    # عدّل حسب الحاجة
npm run build && npm start
```

المتطلبات: Node.js ≥ 18، أي خادم Linux (ذاكرة 512 م.ب تكفي).

---

## 🗂️ خدمات مصدر أخرى

| freereels | melolo | moboreels | goodshort |
|---|---|
| [بدون قيود مدفوعة](https://github.com/beranalpa/FreeReels-API-Free) | [فك تشفير DRM](https://github.com/beranalpa/Melolo-API-Free) | [فتح كامل](https://github.com/beranalpa/MoboReels-API-Free) | [فتح بالإعلانات 1080p](https://github.com/beranalpa/GoodShort-API-Free) |

## 🆘 الدعم

- مفتاح API مجاني وأسئلة: [@dramaboxplusbot](https://t.me/dramaboxplusbot)
- الكونسول المباشر: https://api-pro.hoshiyomi.my.id/docs/dramabox

---

<div align="center">

**كود مصدر كامل. استضافة ذاتية. جاهز لإعادة البيع. واجهتك، قواعدك.**

</div>
