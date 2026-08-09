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

**ランタイム:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**パッケージ:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**言語:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat&label=%E7%8F%BE%E5%9C%A8%E5%9C%B0)](README.ja.md)
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

[Blueprin](blueprin-app.vercel.app) — インドネシアの建設向けプロフェッショナル建築予算プラットフォーム — 用の**プラグイン**、**コネクタ**、**拡張機能**、**統合**を構築するための公式SDK。

## なぜ Blueprin SDK？

Blueprinのコアインフラを再実装せずに、本番環境対応の拡張機能を構築します。

- **プラグインシステム** — ホストアプリを変更せずにBlueprinを拡張
- **フック＆イベント** — ライフサイクルイベントに反応し、動作をカスタマイズ
- **コネクタ** — 外部サービスやサプライヤーと統合
- **フォーマルエンジン** — カスタムビジネスルールでRAB計算を拡張
- **UIコンポーネント** — ネイティブ風のReactプラグインインターフェースを構築
- **サンドボックスランタイム** — プラグインの実行とネットワークアクセスを制御
- **TypeScriptファースト** — 完全な型定義とESM/CJSサポート

## 機能

- **プラグインシステム** — ライフサイクルフックでプラグインの登録、有効化、無効化、管理
- **イベントバス** — プラグ間通信のためのpub/subシステム
- **フックレジストリ** — 機能拡張のためのbefore/afterライフサイクルフック
- **ストレージアダプタ** — localStorage + Supabaseハイブリッドストレージ（SSRガード付き）
- **ドメインクライアント** — プロジェクト、素材、RAB、スケジュール、マーケットプレース、労働力モジュール
- **UIコンポーネント** — プラグインインターフェース構築用Reactコンポーネント
- **コネクタSDK** — 外部サービスとの統合を構築
- **TypeScriptサポート** — 完全な型定義を含む

## アーキテクチャ

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
     プラグイン  イベント    フック     ストレージ  コネクタ
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  ドメインクライアント  |
                    +---------------------+
                    | プロジェクト          |
                    | 素材                 |
                    | RAB                  |
                    | スケジュール          |
                    | マーケットプレース     |
                    | 労働力               |
                    +---------------------+
```

## インストール

```bash
npm install @alvinahmad/blueprin-sdk
# または
pnpm add @alvinahmad/blueprin-sdk
# または
yarn add @alvinahmad/blueprin-sdk
```

## クイックスタート

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

## 最初のプラグインを作成

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('プロジェクト作成:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('RAB合計:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('プラグイン無効化');
  },
});
```

または公式CLIで新しいプラグインをスキャフォールド：

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## 含まれるもの

```
@alvinahmad/blueprin-sdk
│
├── Core
├── プラグイン
├── フック
├── イベント
├── ストレージ
├── コネクタ
├── UI
│
├── プロジェクト
├── 素材
├── RAB
├── スケジュール
├── マーケットプレース
├── 労働力
└── レポート
```

すべてのモジュールはツリーシャッキングをサポートし、サブパスインポートとして利用可能：

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## 例

| 例 | 説明 |
|---|------|
| [Hello Plugin](example/hello_plugin/) | 最もシンプルなプラグイン |
| [RAB Generator](example/rab_generator/) | AIによるRAB生成 |
| [WhatsApp Sync](example/whatsapp_sync/) | WhatsApp通知 |
| [Material Connector](example/material_connector/) | サプライヤーシンク |
| [Custom Report](example/custom_report/) | レポート生成 |

## 互換性

| 環境 | サポート |
|---|---|
| Node.js 18 | Yes |
| Node.js 20 | Yes |
| Node.js 22 | Yes |
| React 18 | Yes |
| React 19 | 実験的 |
| ESM | Yes |
| CommonJS | Yes |
| TypeScript 5.8+ | Yes |

## セキュリティモデル

Blueprinプラグインはホスト制御の権限下で実行されます。

| ケパビリティ | デフォルト | ホスト制御 |
|---|---|---|
| プラグイン実行 | 有効 | ライフサイクル制御 |
| 外部ネットワーク | 無効 | 許可リスト必要 |
| フック | 有効 | 200ms タイムアウト |
| ストレージ | 制限付き | アダプタ制御 |
| UI | 有効 | Reactサンドボックス |

脆弱性の報告については、[セキュリティポリシー](SECURITY.md)をご覧ください。

## ドキュメント

- [完全なドキュメント](https://blueprin-docs.vercel.app)
- [はじめに](docs/getting-started/)
- [プラグイン開発](docs/plugin-development/)
- [フック＆イベント](docs/hooks/)
- [UIコンポーネント](docs/ui-components/)
- [ストレージ](docs/storage/)
- [コネクタ](docs/connectors/)
- [テスト](docs/testing/)
- [公開](docs/publishing/)

## コントリビューション

コントリビューションを歓迎します！詳細は[コントリビューションガイド](CONTRIBUTING.md)をご覧ください。

## コミュニティ

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — 質問、アイデア共有、他の開発者との交流
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — バグ報告と機能リクエスト

## ライセンス

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> 翻訳は英語のドキュメントより遅れる場合があります。英語READMEが正典です。
