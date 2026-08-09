<div align="center">

# Blueprin SDK

<!-- Layer 1 -- Trust -->
[![CI Build & Test](https://github.com/qalvinahmad/blueprin-sdk/actions/workflows/ci.yml/badge.svg)](https://github.com/qalvinahmad/blueprin-sdk/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk.svg)](https://www.npmjs.com/package/@alvinahmad/blueprin-sdk)
[![npm downloads](https://img.shields.io/npm/dm/@alvinahmad/blueprin-sdk.svg)](https://www.npmjs.com/package/@alvinahmad/blueprin-sdk)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Latest Release](https://img.shields.io/github/v/release/qalvinahmad/blueprin-sdk)](https://github.com/qalvinahmad/blueprin-sdk/releases)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/qalvinahmad/blueprin-sdk/badge)](https://api.securityscorecards.dev/projects/github.com/qalvinahmad/blueprin-sdk)
[![Security Policy](https://img.shields.io/badge/Security-Security%20Policy-blue)](SECURITY.md)

<!-- Layer 2 -- Quality -->
[![Code Coverage](https://img.shields.io/codecov/c/github/qalvinahmad/blueprin-sdk?logo=codecov&logoColor=white)](https://codecov.io/gh/qalvinahmad/blueprin-sdk)
[![Code Quality](https://img.shields.io/codefactor/grade/github/qalvinahmad/blueprin-sdk?logo=codefactor&logoColor=white)](https://www.codefactor.io/repository/github/qalvinahmad/blueprin-sdk/overview/main)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg?logo=dependabot&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/network/updates)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Code Style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?logo=prettier&logoColor=white)](https://github.com/prettier/prettier)

<!-- Layer 3 -- Community -->
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Contributors](https://img.shields.io/github/contributors/qalvinahmad/blueprin-sdk?color=green)](https://github.com/qalvinahmad/blueprin-sdk/graphs/contributors)
[![Discussions](https://img.shields.io/github/discussions/qalvinahmad/blueprin-sdk?logo=github&logoColor=white)](https://github.com/qalvinahmad/blueprin-sdk/discussions)

**Среда выполнения:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**Пакет:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**Языки:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat)](README.zh.md)
[![Français](https://img.shields.io/badge/Fran%C3%A7ais-0052CC?style=flat)](README.fr.md)
[![Español](https://img.shields.io/badge/Espa%C3%B1ol-D80027?style=flat)](README.es.md)
[![Deutsch](https://img.shields.io/badge/Deutsch-000000?style=flat)](README.de.md)
[![Português](https://img.shields.io/badge/Portugu%C3%AAs-009B3A?style=flat)](README.pt.md)
[![Русский](https://img.shields.io/badge/%D0%A0%D1%83%D1%81%D1%81%D0%BA%D0%B8%D0%B9-0039A6?style=flat&label=%D0%92%D1%8B%20%D0%B7%D0%B4%D0%B5%D1%81%D1%8C)](README.ru.md)

</div>

<br/>
<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=1QKFSHyeVr75XTAiYaz7UYojd16srcj6R" alt="Blueprin App" width="100%" />
</div>
<br/>

Официальный SDK для создания **плагинов**, **коннекторов**, **расширений** и **интеграций** для [Blueprin](blueprin-app.vercel.app) -- профессиональная платформа архитектурного бюджетирования для строительства в Индонезии.

## Почему Blueprin SDK?

Создавайте готовые к продакшну расширения для Blueprin без повторной реализации его базовой инфраструктуры.

- **Система плагинов** -- Расширяйте Blueprin без изменения хост-приложения
- **Хуки и события** -- Реагируйте на события жизненного цикла и настраивайте поведение
- **Коннекторы** -- Интегрируйте внешние сервисы и поставщиков
- **Движок формул** -- Расширяйте расчеты RAB пользовательскими бизнес-правилами
- **UI компоненты** -- Создавайте нативные интерфейсы плагинов на React
- **Песочница выполнения** -- Управляйте выполнением плагинов и сетевым доступом
- **TypeScript прежде всего** -- Полные определения типов и поддержка ESM/CJS

## Возможности

- **Система плагинов** -- Регистрируйте, активируйте, деактивируйте и управляйте плагинами с хуками жизненного цикла
- **Шина событий** -- Система pub/sub для общения между плагинами
- **Реестр хуков** -- Хуки before/after жизненного цикла для расширения функциональности
- **Адаптер хранилища** -- Гибридное хранилище localStorage + Supabase с защитой SSR
- **Доменные клиенты** -- Модули Проект, Материалы, RAB, Расписание, Маркетплейс и Рабочая сила
- **UI компоненты** -- Компоненты React для создания интерфейсов плагинов
- **SDK Коннектора** -- Создавайте интеграции с внешними сервисами
- **Поддержка TypeScript** -- Полные определения типов включены

## Архитектура

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
     Плагины   События     Хуки    Хранилище  Коннекторы
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  Доменные клиенты   |
                    +---------------------+
                    | Проект              |
                    | Материалы           |
                    | RAB                 |
                    | Расписание          |
                    | Маркетплейс         |
                    | Рабочая сила        |
                    +---------------------+
```

## Установка

```bash
npm install @alvinahmad/blueprin-sdk
# или
pnpm add @alvinahmad/blueprin-sdk
# или
yarn add @alvinahmad/blueprin-sdk
```

## Быстрый старт

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

## Создайте свой первый плагин

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('Проект создан:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('Итого RAB:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('Плагин деактивирован');
  },
});
```

Или создайте новый плагин с помощью официального CLI:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## Что включено

```
@alvinahmad/blueprin-sdk
|
+-- Core
+-- Плагины
+-- Хуки
+-- События
+-- Хранилище
+-- Коннекторы
+-- UI
|
+-- Проект
+-- Материалы
+-- RAB
+-- Расписание
+-- Маркетплейс
+-- Рабочая сила
+-- Отчеты
```

Все модули поддерживают tree-shaking и доступны как subpath imports:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## Примеры

| Пример | Описание |
|--------|----------|
| [Hello Plugin](example/hello_plugin/) | Самый простой плагин |
| [RAB Generator](example/rab_generator/) | Генерация RAB с ИИ |
| [WhatsApp Sync](example/whatsapp_sync/) | Уведомления WhatsApp |
| [Material Connector](example/material_connector/) | Синхронизация поставщиков |
| [Custom Report](example/custom_report/) | Генерация отчетов |

## Совместимость

| Среда | Поддерживается |
|---|---|
| Node.js 18 | Да |
| Node.js 20 | Да |
| Node.js 22 | Да |
| React 18 | Да |
| React 19 | Экспериментальный |
| ESM | Да |
| CommonJS | Да |
| TypeScript 5.8+ | Да |

## Модель безопасности

Плагины Blueprin работают под контролем разрешений хоста.

| Возможность | По умолчанию | Контроль хоста |
|---|---|---|
| Выполнение плагина | Включено | Контроль жизненного цикла |
| Внешняя сеть | Отключено | Требуется список разрешений |
| Хуки | Включено | Таймаут 200мс |
| Хранилище | Ограничено | Контроль адаптером |
| UI | Включено | Песочница React |

Для сообщения об уязвимостях смотрите [Политику безопасности](SECURITY.md).

## Документация

- [Полная документация](https://blueprin-docs.vercel.app)
- [Начало работы](docs/getting-started/)
- [Разработка плагинов](docs/plugin-development/)
- [Хуки и события](docs/hooks/)
- [UI компоненты](docs/ui-components/)
- [Хранилище](docs/storage/)
- [Коннекторы](docs/connectors/)
- [Тестирование](docs/testing/)
- [Публикация](docs/publishing/)

## Участие

Мы приветствуем вклад! Ознакомьтесь с [Руководством по участию](CONTRIBUTING.md) для подробностей.

## Сообщество

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) -- Задавайте вопросы, делитесь идеями и общайтесь с другими разработчиками
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) -- Сообщайте об ошибках и запрашивайте функции

## Лицензия

MIT &copy; [qalvinahmad](https://github.com/qalvinahmad)

---

> Переводы могут отставать от англоязычной документации. Английский README является каноническим источником.
