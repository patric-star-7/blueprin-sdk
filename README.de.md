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

**Laufzeitumgebung:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**Paket:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**Sprachen:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat)](README.zh.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-0052CC?style=flat)](README.fr.md)
[![Español](https://img.shields.io/badge/Espa%C3%B1ol-D80027?style=flat)](README.es.md)
[![Deutsch](https://img.shields.io/badge/Deutsch-000000?style=flat&label=Du%20bist%20hier)](README.de.md)
[![Português](https://img.shields.io/badge/Portugu%C3%AAs-009B3A?style=flat)](README.pt.md)
[![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0039A6?style=flat)](README.ru.md)

</div>

<br/>
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1QKFSHyeVr75XTAiYaz7UYojd16srcj6R" alt="Blueprin App" width="100%" />
</div>
<br/>

Offizielles SDK zum Erstellen von **Plugins**, **Connectoren**, **Erweiterungen** und **Integrationen** für [Blueprin](blueprin-app.vercel.app) — die professionelle architektonische Budgetierungsplattform für das Bauwesen in Indonesien.

## Warum Blueprin SDK?

Erstellen Sie produktionsfertige Erweiterungen für Blueprin, ohne die Kerninfrastruktur neu zu implementieren.

- **Plugin-System** — Erweitern Sie Blueprin ohne die Host-App zu modifizieren
- **Hooks & Events** — Reagieren Sie auf Lifecycle-Events und passen Sie das Verhalten an
- **Connectoren** — Integrieren Sie externe Dienste und Lieferanten
- **Formel-Engine** — Erweitern Sie RAB-Berechnungen mit benutzerdefinierten Geschäftsregeln
- **UI-Komponenten** — Erstellen Sie nativ aussehende React Plugin-Oberflächen
- **Sandbox-Laufzeitumgebung** — Steuern Sie Plugin-Ausführungen und Netzwerkzugriff
- **TypeScript-first** — Vollständige Typdefinitionen und ESM/CJS-Unterstützung

## Funktionen

- **Plugin-System** — Registrieren, aktivieren, deaktivieren und verwalten Sie Plugins mit Lifecycle-Hooks
- **Event-Bus** — Pub/sub-System für die Kommunikation zwischen Plugins
- **Hook-Registry** — Before/after Lifecycle-Hooks zur Funktionalitätserweiterung
- **Storage-Adapter** — Hybrid-Speicher localStorage + Supabase mit SSR-Schutz
- **Domain-Clients** — Module Projekt, Material, RAB, Zeitplan, Marktplatz und Arbeitskräfte
- **UI-Komponenten** — React-Komponenten zum Erstellen von Plugin-Oberflächen
- **Connector-SDK** — Erstellen Sie Integrationen mit externen Diensten
- **TypeScript-Unterstützung** — Vollständige Typdefinitionen enthalten

## Architektur

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
     Plugins   Events       Hooks     Storage   Connectoren
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  Domain-Clients     |
                    +---------------------+
                    | Projekt             |
                    | Material            |
                    | RAB                 |
                    | Zeitplan            |
                    | Marktplatz          |
                    | Arbeitskräfte        |
                    +---------------------+
```

## Installation

```bash
npm install @alvinahmad/blueprin-sdk
# oder
pnpm add @alvinahmad/blueprin-sdk
# oder
yarn add @alvinahmad/blueprin-sdk
```

## Schnellstart

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

## Erstellen Sie Ihr erstes Plugin

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('Projekt erstellt:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('RAB Gesamt:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('Plugin deaktiviert');
  },
});
```

Oder erstellen Sie ein neues Plugin mit dem offiziellen CLI:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## Enthaltenes

```
@alvinahmad/blueprin-sdk
│
├── Core
├── Plugins
├── Hooks
├── Events
├── Storage
├── Connectoren
├── UI
│
├── Projekt
├── Material
├── RAB
├── Zeitplan
├── Marktplatz
├── Arbeitskräfte
└── Berichte
```

Alle Module unterstützen Tree-Shaking und sind als Subpath-Imports verfügbar:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## Beispiele

| Beispiel | Beschreibung |
|----------|--------------|
| [Hello Plugin](example/hello_plugin/) | Einfachstes Plugin |
| [RAB Generator](example/rab_generator/) | KI-gestützte RAB-Generierung |
| [WhatsApp Sync](example/whatsapp_sync/) | WhatsApp-Benachrichtigungen |
| [Material Connector](example/material_connector/) | Lieferanten-Synchronisation |
| [Custom Report](example/custom_report/) | Berichtgenerierung |

## Kompatibilität

| Umgebung | Unterstützt |
|---|---|
| Node.js 18 | Ja |
| Node.js 20 | Ja |
| Node.js 22 | Ja |
| React 18 | Ja |
| React 19 | Experimentell |
| ESM | Ja |
| CommonJS | Ja |
| TypeScript 5.8+ | Ja |

## Sicherheitsmodell

Blueprin-Plugins laufen unter host-kontrollierten Berechtigungen.

| Fähigkeit | Standard | Host-Kontrolle |
|---|---|---|
| Plugin-Ausführung | Aktiviert | Lifecycle-kontrolliert |
| Externes Netzwerk | Deaktiviert | Allowlist erforderlich |
| Hooks | Aktiviert | 200ms Timeout |
| Storage | Eingeschränkt | Adapter-kontrolliert |
| UI | Aktiviert | React-Sandbox |

Für Schwachstellenmeldungen siehe [Sicherheitsrichtlinie](SECURITY.md).

## Dokumentation

- [Vollständige Dokumentation](https://blueprin-docs.vercel.app)
- [Erste Schritte](docs/getting-started/)
- [Plugin-Entwicklung](docs/plugin-development/)
- [Hooks & Events](docs/hooks/)
- [UI-Komponenten](docs/ui-components/)
- [Storage](docs/storage/)
- [Connectoren](docs/connectors/)
- [Testing](docs/testing/)
- [Veröffentlichung](docs/publishing/)

## Beiträge

Wir begrüßen Beiträge! Bitte lesen Sie unseren [Beitragsleitfaden](CONTRIBUTING.md) für Details.

## Gemeinschaft

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — Stellen Sie Fragen, teilen Sie Ideen und verbinden Sie sich mit anderen Entwicklern
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — Melden Sie Fehler und fordern Sie Funktionen an

## Lizenz

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> Übersetzungen können hinter der englischen Dokumentation zurückbleiben. Die englische README ist die kanonische Quelle.
