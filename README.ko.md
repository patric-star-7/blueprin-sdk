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

**런타임:**
![Node.js](https://img.shields.io/badge/Node.js-%3E%3D18.0.0-339933?style=flat&logo=node.js&logoColor=white) ![Browser](https://img.shields.io/badge/Browser-Chrome%20%7C%20Firefox%20%7C%20Safari%20%7C%20Edge-4285F4?style=flat&logo=googlechrome&logoColor=white) ![React](https://img.shields.io/badge/React-%3E%3D18.0.0-61DAFB?style=flat&logo=react&logoColor=white)

**패키지:**
![npm](https://img.shields.io/npm/v/@alvinahmad/blueprin-sdk?style=flat&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8+-3178C6?style=flat&logo=typescript&logoColor=white) ![Module](https://img.shields.io/badge/Module-ESM%20%2B%20CJS-blueviolet?style=flat) ![Node](https://img.shields.io/badge/Node-%3E%3D18-339933?style=flat&logo=node.js&logoColor=white)

**언어:**
[![English](https://img.shields.io/badge/English-0052CC?style=flat)](README.md)
[![Bahasa Indonesia](https://img.shields.io/badge/Bahasa_Indonesia-FF0000?style=flat)](README.id.md)
[![العربية](https://img.shields.io/badge/العربية-000000?style=flat)](README.ar.md)
[![日本語](https://img.shields.io/badge/日本語-BC002D?style=flat)](README.ja.md)
[![한국어](https://img.shields.io/badge/한국어-003478?style=flat&label=%ED%98%84%EC%9E%AC%EC%9C%88)](README.ko.md)
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

[Blueprin](blueprin-app.vercel.app) — 인도네시아 건설 전문 건축 예산 플랫폼 — 을 위한 **플러그인**, **커넥터**, **확장**, **통합**을 구축하는 공식 SDK입니다.

## 왜 Blueprin SDK인가?

Blueprin의 핵심 인프라를 재구현하지 않고 프로덕션 준비 확장을 구축하세요.

- **플러그인 시스템** — 호스트 앱을 수정하지 않고 Blueprin 확장
- **훅 및 이벤트** — 라이프사이클 이벤트에 반응하고 동작을 커스터마이즈
- **커넥터** — 외부 서비스 및 공급업체와 통합
- **수식 엔진** - 사용자 정의 비즈니스 규칙으로 RAB 계산 확장
- **UI 컴포넌트** — 네이티브 느낌의 React 플러그인 인터페이스 구축
- **샌드박스 런타임** — 플러그인 실행 및 네트워크 액세스 제어
- **TypeScript 퍼스트** — 완전한 타입 정의 및 ESM/CJS 지원

## 기능

- **플러그인 시스템** — 라이프사이클 훅으로 플러그인 등록, 활성화, 비활성화, 관리
- **이벤트 버스** — 플러그인 간 통신을 위한 pub/sub 시스템
- **훅 레지스트리** — 기능 확장을 위한 before/after 라이프사이클 훅
- **스토리지 어댑터** — localStorage + Supabase 하이브리드 스토리지 (SSR 가드 포함)
- **도메인 클라이언트** — 프로젝트, 자재, RAB, 일정, 마켓플레이스, 인력 모듈
- **UI 컴포넌트** — 플러그인 인터페이스 구축용 React 컴포넌트
- **커넥터 SDK** — 외부 서비스와의 통합 구축
- **TypeScript 지원** — 완전한 타입 정의 포함

## 아키텍처

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
     플러그인   이벤트      훅       스토리지   커넥터
        |          |           |           |          |
        +----------+-----------+-----------+----------+
                               |
                    +----------v----------+
                    |  도메인 클라이언트    |
                    +---------------------+
                    | 프로젝트             |
                    | 자재                |
                    | RAB                 |
                    | 일정                |
                    | 마켓플레이스         |
                    | 인력                |
                    +---------------------+
```

## 설치

```bash
npm install @alvinahmad/blueprin-sdk
# 또는
pnpm add @alvinahmad/blueprin-sdk
# 또는
yarn add @alvinahmad/blueprin-sdk
```

## 빠른 시작

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

## 첫 번째 플러그인 만들기

```javascript
import { definePlugin } from '@alvinahmad/blueprin-sdk';

export default definePlugin({
  id: 'my-first-plugin',
  name: 'My First Plugin',
  version: '1.0.0',
  description: 'My first Blueprin plugin',

  activate(ctx) {
    ctx.events.on('blueprin:project:created', (data) => {
      console.log('프로젝트 생성:', data.project.name);
    });

    ctx.hooks.register('blueprin:after:rab:calculate', (data) => {
      console.log('RAB 합계:', data.result.total);
      return data;
    });

    return {
      api: {
        getVersion: () => '1.0.0',
      },
    };
  },

  deactivate(instance) {
    console.log('플러그인 비활성화');
  },
});
```

또는 공식 CLI로 새 플러그인을 스캐폴딩:

```bash
npx create-blueprin-plugin my-plugin
cd my-plugin
npm install
npm run dev
```

## 포함된 항목

```
@alvinahmad/blueprin-sdk
│
├── Core
├── 플러그인
├── 훅
├── 이벤트
├── 스토리지
├── 커넥터
├── UI
│
├── 프로젝트
├── 자재
├── RAB
├── 일정
├── 마켓플레이스
├── 인력
└── 리포트
```

모든 모듈은 트리 셰이킹을 지원하며 서브패스 임포트로 사용 가능:

```javascript
import { BlueprinSDK } from '@alvinahmad/blueprin-sdk';
import { definePlugin } from '@alvinahmad/blueprin-sdk/core';
import { ProjectClient } from '@alvinahmad/blueprin-sdk/project';
```

## 예제

| 예제 | 설명 |
|------|------|
| [Hello Plugin](example/hello_plugin/) | 가장 간단한 플러그인 |
| [RAB Generator](example/rab_generator/) | AI 기반 RAB 생성 |
| [WhatsApp Sync](example/whatsapp_sync/) | WhatsApp 알림 |
| [Material Connector](example/material_connector/) | 공급업체 동기화 |
| [Custom Report](example/custom_report/) | 리포트 생성 |

## 호환성

| 환경 | 지원 |
|---|---|
| Node.js 18 | Yes |
| Node.js 20 | Yes |
| Node.js 22 | Yes |
| React 18 | Yes |
| React 19 | 실험적 |
| ESM | Yes |
| CommonJS | Yes |
| TypeScript 5.8+ | Yes |

## 보안 모델

Blueprin 플러그인은 호스트 제어 권한 아래에서 실행됩니다.

| 기능 | 기본값 | 호스트 제어 |
|---|---|---|
| 플러그인 실행 | 활성화 | 라이프사이클 제어 |
| 외부 네트워크 | 비활성화 | 허용 목록 필요 |
| 훅 | 활성화 | 200ms 타임아웃 |
| 스토리지 | 제한됨 | 어댑터 제어 |
| UI | 활성화 | React 샌드박스 |

취약점 보고는 [보안 정책](SECURITY.md)을 참조하세요.

## 문서

- [전체 문서](https://blueprin-docs.vercel.app)
- [시작하기](docs/getting-started/)
- [플러그인 개발](docs/plugin-development/)
- [훅 및 이벤트](docs/hooks/)
- [UI 컴포넌트](docs/ui-components/)
- [스토리지](docs/storage/)
- [커넥터](docs/connectors/)
- [테스트](docs/testing/)
- [배포](docs/publishing/)

## 기여

기여를 환영합니다! 자세한 내용은 [기여 가이드](CONTRIBUTING.md)를 참조하세요.

## 커뮤니티

- [GitHub Discussions](https://github.com/qalvinahmad/blueprin-sdk/discussions) — 질문, 아이디어 공유, 다른 개발자와 연결
- [Issue Tracker](https://github.com/qalvinahmad/blueprin-sdk/issues) — 버그 보고 및 기능 요청

## 라이선스

MIT © [qalvinahmad](https://github.com/qalvinahmad)

---

> 번역이 영어 문서보다 늦어질 수 있습니다. 영어 README가 권위 있는 소스입니다.
