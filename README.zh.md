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

**运行环境:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**包:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**语言:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat)](README.ko.md)
[![中文](https://img.shields.io/badge/中文-DE2910?style=flat&label=%E5%BD%93%E5%89%8D%E4%BD%8D)](README.zh.md)
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

[Blueprin](blueprin-app.vercel.app) — 印度尼西亚专业建筑预算平台 — 的官方 SDK，用于构建**插件**、**连接器**、**扩展**和**集成**。

## 为什么选择 Blueprin SDK？

无需重新实现 Blueprin 的核心基础设施，即可构建生产就绪的扩展。

- **插件系统** — 无需修改宿主应用即可扩展 Blueprin
- **钩子和事件** — 响应生命周期事件并自定义行为
- **连接器** — 集成外部服务和供应商
- **公式引擎** — 使用自定义业务规则扩展 RAB 计算
- **UI 组件** — 构建原生风格的 React 插件界面
- **沙箱运行时** — 控制插件执行和网络访问
- **TypeScript 优先** — 完整的类型定义和 ESM/CJS 支持

## 功能

- **插件系统** — 使用生命周期钩子注册、激活、停用和管理插件
- **事件总线** — 插件间通信的 pub/sub 系统
- **钩子注册表** — 用于扩展功能的 before/after 生命周期钩子
- **存储适配器** — localStorage + Supabase 混合存储（带 SSR 保护）
- **领域客户端** — 项目、材料、RAB、日程、市场和劳动力模块
- **UI 组件** — 用于构建插件界面的 React 组件
- **连接器 SDK** — 构建与外部服务的集成
- **TypeScript 支持** — 包含完整的类型定义

## 架构

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
     插件       事件        钩子       存储      连接器
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  领域客户端          |
                    +---------------------+
                    | 项目                |
                    | 材料                |
                    | RAB                 |
                    | 日程                |
                    | 市场                |
                    | 劳动力              |
                    +---------------------+
```

## 安装

```bash
npm install @alvinahmad/blueprin-sdk
# 或
pnpm add @alvinahmad/blueprin-sdk
# 或
yarn add @alvinahmad/blueprin-sdk
```

## 快速开始

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

## 创建您的第一个插件

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('项目创建:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('RAB 总计:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('插件停用');
  },
});
```

或使用官方 CLI 脚手架创建新插件：

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## 包含内容

```
@alvinahmad/blueprin-sdk
│
├── 核心
├── 插件
├── 钩子
├── 事件
├── 存储
├── 连接器
├── UI
│
├── 项目
├── 材料
├── RAB
├── 日程
├── 市场
├── 劳动力
└── 报告
```

所有模块支持树摇优化，可通过子路径导入：

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## 示例

| 示例 | 描述 |
|------|------|
| [Hello Plugin](example/hello_plugin/) | 最简单的插件 |
| [RAB Generator](example/rab_generator/) | AI 驱动的 RAB 生成 |
| [WhatsApp Sync](example/whatsapp_sync/) | WhatsApp 通知 |
| [Material Connector](example/material_connector/) | 供应商同步 |
| [Custom Report](example/custom_report/) | 报告生成 |

## 兼容性

| 环境 | 支持 |
|---|---|
| Node.js 18 | Yes |
| Node.js 20 | Yes |
| Node.js 22 | Yes |
| React 18 | Yes |
| React 19 | 实验性 |
| ESM | Yes |
| CommonJS | Yes |
| TypeScript 5.8+ | Yes |

## 安全模型

Blueprin 插件在宿主控制的权限下运行。

| 能力 | 默认 | 宿主控制 |
|---|---|---|
| 插件执行 | 启用 | 生命周期控制 |
| 外部网络 | 禁用 | 需要允许列表 |
| 钩子 | 启用 | 200ms 超时 |
| 存储 | 受限 | 适配器控制 |
| UI | 启用 | React 沙箱 |

漏洞报告请参阅[安全策略](SECURITY.md)。

## 文档

- [完整文档](https://blueprin-docs.vercel.app)
- [入门](docs/getting-started/)
- [插件开发](docs/plugin-development/)
- [钩子与事件](docs/hooks/)
- [UI 组件](docs/ui-components/)
- [存储](docs/storage/)
- [连接器](docs/connectors/)
- [测试](docs/testing/)
- [发布](docs/publishing/)

## 贡献

欢迎贡献！详情请参阅[贡献指南](CONTRIBUTING.md)。

## 社区

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — 提问、分享想法、与其他开发者交流
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — 报告错误和请求功能

## 许可证

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> 翻译可能落后于英文文档。英文 README 是权威来源。
