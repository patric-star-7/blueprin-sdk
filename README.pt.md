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

**Ambiente de execução:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**Pacote:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**Idiomas:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat)](README.zh.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-0052CC?style=flat)](README.fr.md)
[![Español](https://img.shields.io/badge/Espa%C3%B1ol-D80027?style=flat)](README.es.md)
[![Deutsch](https://img.shields.io/badge/Deutsch-000000?style=flat)](README.de.md)
[![Português](https://img.shields.io/badge/Portugu%C3%AAs-009B3A?style=flat&label=Voc%C3%AA%20est%C3%A1%20aqui)](README.pt.md)
[![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0039A6?style=flat)](README.ru.md)

</div>

<br/>
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1QKFSHyeVr75XTAiYaz7UYojd16srcj6R" alt="Blueprin App" width="100%" />
</div>
<br/>

SDK oficial para construir **plugins**, **conectores**, **extensões** e **integrações** para [Blueprin](blueprin-app.vercel.app) — a plataforma profissional de orçamento arquitetônico para construção na Indonésia.

## Por que Blueprin SDK?

Construa extensões prontas para produção para o Blueprin sem reimplementar sua infraestrutura principal.

- **Sistema de plugins** — Estenda o Blueprin sem modificar o aplicativo host
- **Hooks e eventos** — Reaja a eventos do ciclo de vida e personalize o comportamento
- **Conectores** — Integre serviços externos e fornecedores
- **Motor de fórmulas** — Estenda os cálculos RAB com regras de negócios personalizadas
- **Componentes UI** — Construa interfaces de plugins React nativas
- **Runtime sandboxed** — Controle a execução de plugins e o acesso à rede
- **TypeScript primeiro** — Definições de tipos completas e suporte ESM/CJS

## Funcionalidades

- **Sistema de plugins** — Registre, ative, desative e gerencie plugins com hooks do ciclo de vida
- **Bus de eventos** — Sistema pub/sub para comunicação entre plugins
- **Registro de hooks** — Hooks before/after do ciclo de vida para estender funcionalidades
- **Adaptador de armazenamento** — Armazenamento híbrido localStorage + Supabase com proteções SSR
- **Clientes de domínio** — Módulos Projeto, Materiais, RAB, Cronograma, Marketplace e Mão de Obra
- **Componentes UI** — Componentes React para construir interfaces de plugins
- **SDK Conector** — Construa integrações com serviços externos
- **Suporte a TypeScript** — Definições de tipos completas incluídas

## Arquitetura

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
     Plugins  Eventos      Hooks   Armazenamento Conectores
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  Clientes domínio   |
                    +---------------------+
                    | Projeto             |
                    | Materiais           |
                    | RAB                 |
                    | Cronograma          |
                    | Marketplace         |
                    | Mão de Obra         |
                    +---------------------+
```

## Instalação

```bash
npm install @alvinahmad/blueprin-sdk
# ou
pnpm add @alvinahmad/blueprin-sdk
# ou
yarn add @alvinahmad/blueprin-sdk
```

## Início rápido

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

## Crie seu primeiro plugin

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('Projeto criado:', data.project.name);
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
    console.log('Plugin desativado');
  },
});
```

Ou crie um novo plugin com a CLI oficial:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## Conteúdo incluído

```
@alvinahmad/blueprin-sdk
│
├── Core
├── Plugins
├── Hooks
├── Eventos
├── Armazenamento
├── Conectores
├── UI
│
├── Projeto
├── Materiais
├── RAB
├── Cronograma
├── Marketplace
├── Mão de Obra
└── Relatórios
```

Todos os módulos suportam tree-shaking e estão disponíveis como imports de subcaminhos:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## Exemplos

| Exemplo | Descrição |
|---------|-----------|
| [Hello Plugin](example/hello_plugin/) | Plugin mais simples |
| [RAB Generator](example/rab_generator/) | Geração RAB com IA |
| [WhatsApp Sync](example/whatsapp_sync/) | Notificações WhatsApp |
| [Material Connector](example/material_connector/) | Sincronização de fornecedores |
| [Custom Report](example/custom_report/) | Geração de relatórios |

## Compatibilidade

| Ambiente | Suportado |
|---|---|
| Node.js 18 | Sim |
| Node.js 20 | Sim |
| Node.js 22 | Sim |
| React 18 | Sim |
| React 19 | Experimental |
| ESM | Sim |
| CommonJS | Sim |
| TypeScript 5.8+ | Sim |

## Modelo de segurança

Os plugins Blueprin rodam sob permissões controladas pelo host.

| Capacidade | Padrão | Controle do host |
|---|---|---|
| Execução de plugin | Ativado | Controle do ciclo de vida |
| Rede externa | Desativado | Lista de permissões necessária |
| Hooks | Ativado | Timeout de 200ms |
| Armazenamento | Restrito | Controle por adaptador |
| UI | Ativado | Sandbox React |

Para relatórios de vulnerabilidades, consulte a [Política de Segurança](SECURITY.md).

## Documentação

- [Documentação completa](https://blueprin-docs.vercel.app)
- [Primeiros passos](docs/getting-started/)
- [Desenvolvimento de plugins](docs/plugin-development/)
- [Hooks e eventos](docs/hooks/)
- [Componentes UI](docs/ui-components/)
- [Armazenamento](docs/storage/)
- [Conectores](docs/connectors/)
- [Testes](docs/testing/)
- [Publicação](docs/publishing/)

## Contribuir

Aceitamos contribuições! Consulte nosso [Guia de Contribuição](CONTRIBUTING.md) para mais detalhes.

## Comunidade

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — Faça perguntas, compartilhe ideias e conecte-se com outros desenvolvedores
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — Relate bugs e solicite funcionalidades

## Licença

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> As traduções podem ficar defasadas em relação à documentação em inglês. O README em inglês é a fonte canônica.
