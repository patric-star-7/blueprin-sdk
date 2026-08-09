<div align="center" dir="rtl">

# Blueprin SDK

<!-- Layer 1 — Trust -->
[![CI Build & Test](https://github.com/qalvinahmad/blueprin-sdk/actions/workflows/ci.yml/badge.svg)](https://github.com/qalvinahmad/blueprin-sdk/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk.svg)](https://www.npmjs.com/package/@alvinahmad/blueprin-sdk)
[![npm downloads](https://img.shields.io/npm/dm/@alvinahmad/blueprin-sdk.svg)](https://www.npmjs.com/package/@alvinahmad/blueprin-sdk)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Latest Release](https://img.shields.io/github/v/release/qalvinahmad/blueprin-sdk)](https://github.com/qalvinahmad/blueprin-sdk/releases)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/qalvinahmad/blueprin-sdk/badge)](https://api.securityscorecards.dev/projects/github.com/qalvinahmad/blueprin-sdk)
[![Security Policy](https://img.shields.io/badge/Security-Security%20Policy-blue)](SECURITY.md)

<!-- Layer 2 — Quality -->
[![Code Coverage](https://img.shields.io/codecov/c/github/qalvinahmad/blueprin-sdk?logo=codecov&logoColor=white)](https://codecov.io/gh/qalvinahmad/blueprin-sdk)
[![Code Quality](https://img.shields.io/codefactor/grade/github/qalvinahmad/blueprin-sdk?logo=codefactor&logoColor=white)](https://www.codefactor.io/repository/github/qalvinahmad/blueprin-sdk/overview/main)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg?logo=dependabot&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/network/updates)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Code Style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?logo=prettier&logoColor=white)](https://github.com/prettier/prettier)

<!-- Layer 3 — Community -->
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Contributors](https://img.shields.io/github/contributors/qalvinahmad/blueprin-sdk?color=green)](https://github.com/qalvinahmad/blueprin-sdk/graphs/contributors)
[![Discussions](https://img.shields.io/github/discussions/qalvinahmad/blueprin-sdk?logo=github&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/discussions)

**Runtime:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**Package:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**اللغات:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat&label=%D8%A3%D9%86%D8%AA%D9%85%20%D9%87%D9%86%D8%A7)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat)](README.zh.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-0052CC?style=flat)](README.fr.md)
[![Español](https://img.shields.io/badge/Espa%C3%B1ol-D80027?style=flat)](README.es.md)
[![Deutsch](https://img.shields.io/badge/Deutsch-000000?style=flat)](README.de.md)
[![Português](https://img.shields.io/badge/Portugu%C3%AAs-009B3A?style=flat)](README.pt.md)
[![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0039A6?style=flat)](README.ru.md)

</div>

<br/>
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1QKFSHyeVr75XTAiYaz7UYojd16srcj6R" alt="Blueprin App" width="100%" />
</div>
<br/>

SDK الرسمي لبناء **إضافات** و**موصلات** و**امتدادات** و**تكاملات** لـ [Blueprin](blueprin-app.vercel.app) — منصة الميزانية المعمارية الاحترافية للبناء في إندونيسيا.

## لماذا Blueprin SDK؟

قم ببناء امتدادات جاهزة للإنتاج لـ Blueprin دون إعادة تنفيز البنية التحتية الأساسية.

- **نظام الإضافات** — قم بتوسيع Blueprin دون تعديل التطبيق المضيف
- **الأحداث والخطافات** — استجب لأحداث دورة الحياة وخصّص السلوك
- **الموصلات** — قم بدمج الخدمات الخارجية والموردين
- **محرك الصيغ** — قم بتوسيع حسابات RAB بقواعد عمل مخصصة
- **مكونات واجهة المستخدم** — قم ببناء واجهات إضافات React أصلية
- **بيئة تشغيل معزولة** — التحكم في تنفيذ الإضافات والوصول للشبكة
- **TypeScript أولاً** — تعريفات أنواع كاملة ودعم ESM/CJS

## الميزات

- **نظام الإضافات** — سجّل وفعّل وأوقف وأدر الإضافات مع خطافات دورة الحياة
- **ناقل الأحداث** — نظام pub/sub للاتصال بين الإضافات
- **سجل الخطافات** — خطافات قبل/بعد دورة الحياة لتوسيع الوظائف
- **محرك التخزين** — تخزين هجين localStorage + Supabase مع حماية SSR
- **عملاء المجال** — وحدات المشروع والمواد وRAB والجدول والسوق والقوى العاملة
- **مكونات واجهة المستخدم** — مكونات React لبناء واجهات الإضافات
- **SDK للموصلات** — قم ببناء التكاملات مع الخدمات الخارجية
- **دعم TypeScript** — تعريفات أنواع كاملة مضمنة

## الهيكلة

```
                    +---------------------+
                    |    Blueprin Host    |
                    |       App           |
                    +----------+----------+
                               |
                     +---------v---------+
                     |   Blueprin SDK    |
                     +---------+---------+
                               |
        +----------+-----------+-----------+----------+
        v          v           v           v          v
     الإضافات   الأحداث    الخطافات   التخزين  الموصلات
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  عملاء المجال       |
                    +---------------------+
                    | المشروع             |
                    | المواد              |
                    | RAB                 |
                    | الجدول              |
                    | السوق               |
                    | القوى العاملة       |
                    +---------------------+
```

## التثبيت

```bash
npm install @alvinahmad/blueprin-sdk
# أو
pnpm add @alvinahmad/blueprin-sdk
# أو
yarn add @alvinahmad/blueprin-sdk
```

## البدء السريع

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';

const sdk = new BlueprinSDK({
  appId: 'my-app',
  supabaseUrl: process.env.SUPABASE_URL,
  supabaseKey: process.env.SUPABASE_ANON_KEY,
  debug: true,
});

await sdk.init();

console.log(sdk.getInfo());
// { version: '1.0.1', plugins: 0, hooks: 0, events: 0, initialized: true }
```

## أنشئ إضافتك الأولى

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'إضافتي الأولى',
  version: '1.0.0',
  description: 'إضافتي الأولى لـ Blueprin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('تم إنشاء المشروع:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('إجمالي RAB:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('تم تعطيل الإضافة');
  },
});
```

أو أنشئ إضافة جديدة بأداة CLI الرسمية:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## ما الذي يتضمن

```
@alvinahmad/blueprin-sdk
│
├── Core
├── الإضافات
├── الخطافات
├── الأحداث
├── التخزين
├── الموصلات
├── واجهة المستخدم
│
├── المشروع
├── المواد
├── RAB
├── الجدول
├── السوق
├── القوى العاملة
└── التقارير
```

جميع الوحدات تدعم tree-shaking ومتوفرة كاستيرادات فرعية:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## الأمثلة

| المثال | الوصف |
|--------|-------|
| [Hello Plugin](example/hello_plugin/) | أبسط إضافة |
| [RAB Generator](example/rab_generator/) | إنشاء RAB بالذكاء الاصطناعي |
| [WhatsApp Sync](example/whatsapp_sync/) | إشعارات WhatsApp |
| [Material Connector](example/material_connector/) | مزامنة الموردين |
| [Custom Report](example/custom_report/) | إنشاء تقارير |

## التوافق

| البيئة | مدعوم |
|---|---|
| Node.js 18 | نعم |
| Node.js 20 | نعم |
| Node.js 22 | نعم |
| React 18 | نعم |
| React 19 | تجريبي |
| ESM | نعم |
| CommonJS | نعم |
| TypeScript 5.8+ | نعم |

## نموذج الأمان

إضافات Blueprin تعمل تحت أذونات المضيف المتحكّم.

| القدرة | الافتراضي | التحكم المضيف |
|---|---|---|
| تنفيذ الإضافات | مفعّل | دورة الحياة محكّمة |
| الشبكة الخارجية | معطّل | قائمة إذن مطلوبة |
| الخطافات | مفعّل | مهلة 200 مللي ثانية |
| التخزين | مقيد | محرك محكّم |
| واجهة المستخدم | مفعّل | بيئة React معزولة |

للإبلاغ عن الثغرات، راجع [سياسة الأمان](SECURITY.md).

## التوثيق

- [التوثيق الكامل](https://blueprin-docs.vercel.app)
- [البدء](docs/getting-started/)
- [تطوير الإضافات](docs/plugin-development/)
- [الخطافات والأحداث](docs/hooks/)
- [مكونات واجهة المستخدم](docs/ui-components/)
- [التخزين](docs/storage/)
- [الموصلات](docs/connectors/)
- [الاختبار](docs/testing/)
- [النشر](docs/publishing/)

## المساهمة

نرحب بالمساهمات! يرجى الاطلاع على [دليل المساهمة](CONTRIBUTING.md) للتفاصيل.

## المجتمع

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — اطرح الأسئلة وشارك الأفكار وتواصل مع المطورين الآخرين
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — أبلغ عن الأخطاء واطلب الميزات

## الترخيص

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> قد تتخلف الترجمات عن التوثيق الإنجليزي. ملف README الإنجليبي هو المصدر الموثوق.
