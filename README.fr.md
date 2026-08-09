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
[![Code Quality](https://img.shields.io/codefactor/grade/github/qalvinahmad/blueprin-sdk?logo=codefactor&logoColor=white)](https://www.codefactor.io/repository/github/qalvinahmad/blueprin-sdk/overview/main)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg?logo=dependabot&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/network/updates)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Code Style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?logo=prettier&logoColor=white)](https://github.com/prettier/prettier)

<!-- Layer 3 — Community -->
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Contributors](https://img.shields.io/github/contributors/qalvinahmad/blueprin-sdk?color=green)](https://github.com/qalvinahmad/blueprin-sdk/graphs/contributors)
[![Discussions](https://img.shields.io/github/discussions/qalvinahmad/blueprin-sdk?logo=github&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/discussions)

**Environnement d'exécution:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**Package:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**Langues:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat)](README.zh.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-0052CC?style=flat&label=Vous%20%C3%AAtes%20ici)](README.fr.md)
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

SDK officiel pour construire des **plugins**, **connecteurs**, **extensions** et **intégrations** pour [Blueprin](blueprin-app.vercel.app) — la plateforme professionnelle de budgétisation architecturale pour la construction en Indonésie.

## Pourquoi Blueprin SDK?

Construisez des extensions prêtes pour la production pour Blueprin sans réimplémenter son infrastructure de base.

- **Système de plugins** — Étendez Blueprin sans modifier l'application hôte
- **Hooks et événements** — Réagissez aux événements du cycle de vie et personnalisez le comportement
- **Connecteurs** — Intégrez des services externes et des fournisseurs
- **Moteur de formules** — Étendez les calculs RAB avec des règles métier personnalisées
- **Composants UI** — Construisez des interfaces de plugins React natives
- **Runtime sandboxé** — Contrôlez l'exécution des plugins et l'accès réseau
- **TypeScript en premier** — Définitions de types complètes et support ESM/CJS

## Fonctionnalités

- **Système de plugins** — Enregistrez, activez, désactivez et gérez les plugins avec des hooks du cycle de vie
- **Bus d'événements** — Système pub/sub pour la communication inter-plugins
- **Registre de hooks** — Hooks before/after du cycle de vie pour étendre les fonctionnalités
- **Adaptateur de stockage** — Stockage hybride localStorage + Supabase avec protections SSR
- **Clients domaine** — Modules Projet, Matériaux, RAB, Planning, Marché et Main-d'œuvre
- **Composants UI** — Composants React pour construire les interfaces de plugins
- **SDK Connecteur** — Construisez des intégrations avec des services externes
- **Support TypeScript** — Définitions de types complètes incluses

## Architecture

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
     Plugins  Événements   Hooks    Stockage  Connecteurs
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  Clients domaine    |
                    +---------------------+
                    | Projet              |
                    | Matériaux           |
                    | RAB                 |
                    | Planning            |
                    | Marché              |
                    | Main-d'œuvre        |
                    +---------------------+
```

## Installation

```bash
npm install @alvinahmad/blueprin-sdk
# ou
pnpm add @alvinahmad/blueprin-sdk
# ou
yarn add @alvinahmad/blueprin-sdk
```

## Démarrage rapide

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

## Créez votre premier plugin

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('Projet créé:', data.project.name);
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
    console.log('Plugin désactivé');
  },
});
```

Ou créez un nouveau plugin avec l'CLI officielle:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## Contenu inclus

```
@alvinahmad/blueprin-sdk
│
├── Core
├── Plugins
├── Hooks
├── Événements
├── Stockage
├── Connecteurs
├── UI
│
├── Projet
├── Matériaux
├── RAB
├── Planning
├── Marché
├── Main-d'œuvre
└── Rapports
```

Tous les modules supportent le tree-shaking et sont disponibles en imports de sous-chemins:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## Exemples

| Exemple | Description |
|---------|-------------|
| [Hello Plugin](example/hello_plugin/) | Plugin le plus simple |
| [RAB Generator](example/rab_generator/) | Génération RAB par IA |
| [WhatsApp Sync](example/whatsapp_sync/) | Notifications WhatsApp |
| [Material Connector](example/material_connector/) | Synchronisation fournisseurs |
| [Custom Report](example/custom_report/) | Génération de rapports |

## Compatibilité

| Environnement | Supporté |
|---|---|
| Node.js 18 | Oui |
| Node.js 20 | Oui |
| Node.js 22 | Oui |
| React 18 | Oui |
| React 19 | Expérimental |
| ESM | Oui |
| CommonJS | Oui |
| TypeScript 5.8+ | Oui |

## Modèle de sécurité

Les plugins Blueprin s'exécutent sous les permissions contrôlées par l'hôte.

| Capacité | Par défaut | Contrôle hôte |
|---|---|---|
| Exécution de plugin | Activé | Contrôle du cycle de vie |
| Réseau externe | Désactivé | Liste d'autorisation requise |
| Hooks | Activé | Timeout de 200ms |
| Stockage | Restreint | Contrôle par adaptateur |
| UI | Activé | Sandbox React |

Pour les signalements de vulnérabilités, consultez la [Politique de sécurité](SECURITY.md).

## Documentation

- [Documentation complète](https://blueprin-docs.vercel.app)
- [Commencer](docs/getting-started/)
- [Développement de plugins](docs/plugin-development/)
- [Hooks et événements](docs/hooks/)
- [Composants UI](docs/ui-components/)
- [Stockage](docs/storage/)
- [Connecteurs](docs/connectors/)
- [Tests](docs/testing/)
- [Publication](docs/publishing/)

## Contribuer

Nous accueillons les contributions! Veuillez consulter notre [Guide de contribution](CONTRIBUTING.md) pour plus de détails.

## Communauté

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — Posez des questions, partagez des idées et connectez-vous avec d'autres développeurs
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — Signalez des bugs et demandez des fonctionnalités

## Licence

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> Les traductions peuvent être en retard par rapport à la documentation anglaise. Le README anglais est la source canonique.
