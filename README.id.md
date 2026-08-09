<div align="center">

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

**Bahasa:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat&label=Berada%20di%20sini)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
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

SDK resmi untuk membangun **plugin**, **connector**, **ekstensi** dan **integrasi** untuk [Blueprin](blueprin-app.vercel.app) — platform perencanaan anggaran arsitektur profesional untuk konstruksi di Indonesia.

## Mengapa Blueprin SDK?

Bangun ekstensi production-ready untuk Blueprin tanpa mengimplementasikan ulang infrastruktur intinya.

- **Sistem Plugin** — Perluas Blueprin tanpa memodifikasi host app
- **Hooks & Events** — React terhadap lifecycle event dan sesuaikan perilaku
- **Connector** — Integrasikan layanan eksternal dan supplier
- **Formula Engine** — Perluas kalkulasi RAB dengan aturan bisnis kustom
- **Komponen UI** — Bangun antarmuka plugin React yang natif
- **Runtime Terpasung** — Kendalikan eksekusi plugin dan akses jaringan
- **TypeScript-first** — Definisi tipe lengkap dan dukungan ESM/CJS

## Fitur

- **Sistem Plugin** — Daftarkan, aktifkan, nonaktifkan, dan kelola plugin dengan lifecycle hook
- **Event Bus** — Sistem pub/sub untuk komunikasi antar plugin
- **Hook Registry** — Hook before/after lifecycle untuk memperluas fungsi
- **Storage Adapter** — Hybrid storage localStorage + Supabase dengan SSR guards
- **Domain Clients** — Modul Project, Material, RAB, Schedule, Marketplace, dan Workforce
- **Komponen UI** — Komponen React untuk membangun antarmuka plugin
- **Connector SDK** — Bangun integrasi dengan layanan eksternal
- **Dukungan TypeScript** — Definisi tipe lengkap disertakan

## Arsitektur

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
     Plugins    Events       Hooks      Storage   Connectors
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  Domain Clients     |
                    +---------------------+
                    | Project             |
                    | Material            |
                    | RAB                 |
                    | Schedule            |
                    | Marketplace         |
                    | Workforce           |
                    +---------------------+
```

## Instalasi

```bash
npm install @alvinahmad/blueprin-sdk
# atau
pnpm add @alvinahmad/blueprin-sdk
# atau
yarn add @alvinahmad/blueprin-sdk
```

## Mulai Cepat

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

## Buat Plugin Pertama Anda

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'Plugin Pertama Saya',
  version: '1.0.0',
  description: 'Plugin pertama saya untuk Blueprin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('Proyek dibuat:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('Total RAB:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('Plugin dinonaktifkan');
  },
});
```

Atau generate plugin baru dengan CLI resmi:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## Apa yang Termasuk

```
@alvinahmad/blueprin-sdk
│
├── Core
├── Plugins
├── Hooks
├── Events
├── Storage
├── Connectors
├── UI
│
├── Project
├── Material
├── RAB
├── Schedule
├── Marketplace
├── Workforce
└── Reports
```

Semua modul mendukung tree-shaking dan tersedia sebagai subpath imports:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## Contoh

| Contoh | Deskripsi |
|--------|-----------|
| [Hello Plugin](example/hello_plugin/) | Plugin paling sederhana |
| [RAB Generator](example/rab_generator/) | Generate RAB dengan AI |
| [WhatsApp Sync](example/whatsapp_sync/) | Notifikasi WhatsApp |
| [Material Connector](example/material_connector/) | Sinkronisasi supplier |
| [Custom Report](example/custom_report/) | Generate laporan |

## Kompatibilitas

| Lingkungan | Didukung |
|---|---|
| Node.js 18 | Ya |
| Node.js 20 | Ya |
| Node.js 22 | Ya |
| React 18 | Ya |
| React 19 | Eksperimental |
| ESM | Ya |
| CommonJS | Ya |
| TypeScript 5.8+ | Ya |

## Model Keamanan

Plugin Blueprin berjalan di bawah kontrol permission host.

| Kemampuan | Default | Kontrol Host |
|---|---|---|
| Eksekusi plugin | Aktif | Lifecycle dikontrol |
| Jaringan eksternal | Nonaktif | Allowlist diperlukan |
| Hooks | Aktif | Timeout 200ms |
| Storage | Terbatas | Adapter dikontrol |
| UI | Aktif | React sandbox |

Untuk pelaporan kerentanan, lihat [Kebijakan Keamanan](SECURITY.md).

## Dokumentasi

- [Dokumentasi Lengkap](https://blueprin-docs.vercel.app)
- [Memulai](docs/getting-started/)
- [Pengembangan Plugin](docs/plugin-development/)
- [Hook & Event](docs/hooks/)
- [Komponen UI](docs/ui-components/)
- [Penyimpanan](docs/storage/)
- [Connector](docs/connectors/)
- [Pengujian](docs/testing/)
- [Penerbitan](docs/publishing/)

## Contributing

Kami menyambut kontribusi! Silakan lihat [Panduan Kontribusi](CONTRIBUTING.md) untuk detail.

## Komunitas

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — Ajukan pertanyaan, bagikan ide, dan terhubung dengan developer lain
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — Laporkan bug dan minta fitur

## Lisensi

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> Terjemahan mungkin tertinggal dari dokumentasi Bahasa Inggris. README Bahasa Inggris adalah sumber kanonik.
