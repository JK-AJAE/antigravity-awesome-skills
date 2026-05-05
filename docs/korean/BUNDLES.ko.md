# 📦 Antigravity 스킬 번들 (Skill Bundles)

> **역할 및 전문 분야별로 엄선된 스킬 컬렉션입니다.** 어디서부터 시작해야 할지 모르겠나요? 본인의 역할에 맞는 번들을 선택하여 최적화된 스킬 세트를 확인해 보세요.

> 이 팩들은 사용자를 위해 선별된 스타터 추천 리스트입니다. `data/bundles.json`에 생성된 번들 ID들은 더 넓은 범위의 카탈로그/워크플로우 그룹이며, 아래의 편집 팩들과 1:1로 매칭될 필요는 없습니다.

> **중요:** 번들은 설치 가능한 플러그인 하위 세트 및 활성화 프리셋이며, `@web-wizard`나 `/essentials-bundle`처럼 직접 호출하는 '거대 스킬'이 아닙니다. 팩에 나열된 개별 스킬을 사용하거나, 전용 마켓플레이스 플러그인으로 번들을 설치하거나, 활성화 스크립트를 사용하여 현재 Antigravity 디렉토리에서 해당 번들의 스킬만 활성화하여 사용하세요.

> **플러그인 호환성:** 루트 플러그인과 번들 플러그인은 '플러그인 안전(plugin-safe)' 스킬만 게시합니다. 번들에 `pending hardening`이라고 표시되어 있다면, 해당 스킬은 저장소에 존재하지만 아직 대상 플랫폼용으로 게시되지 않았음을 의미합니다. `Requires manual setup`은 번들 설치는 가능하지만, 하나 이상의 포함된 스킬을 처음 사용하기 전에 명시적인 설정 단계가 필요함을 의미합니다.

---

## 🚀 빠른 시작 (Quick Start)

1. **저장소 또는 번들 플러그인 설치:**

   ```bash
   npx antigravity-awesome-skills
   # 또는 수동으로 클론
   git clone https://github.com/sickn33/antigravity-awesome-skills.git .agent/skills
   ```

2. 아래 리스트에서 본인의 역할이나 관심사에 맞는 **번들을 선택**하세요.

3. AI 어시스턴트에서 **번들 플러그인 또는 개별 스킬을 사용**하세요:
   - **Claude Code**: 일치하는 마켓플레이스 번들 플러그인을 설치하거나, `>> /스킬이름 help me...` 호출
   - **Cursor**: 채팅창에서 `@스킬이름` 입력
   - **Gemini CLI**: `Use 스킬이름...` 호출

전체 설치 대신 특정 번들만 활성화된 하위 세트로 동작하게 하려면 다음을 사용하세요:

- **macOS/Linux**: `./scripts/activate-skills.sh --clear Essentials`
- **Windows**: `.\scripts\activate-skills.bat --clear Essentials`

---

## 🚀 필수 및 핵심 (Essentials & Core)

### 🚀 "Essentials" 스타터 팩
*모든 사용자용. 가장 먼저 설치하세요.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`concise-planning`**](../../skills/concise-planning/): 항상 계획부터 시작하세요.
- [**`lint-and-validate`**](../../skills/lint-and-validate/): 코드 품질을 자동으로 유지하세요.
- [**`git-pushing`**](../../skills/git-pushing/): 작업 내용을 안전하게 저장하세요.
- [**`kaizen`**](../../skills/kaizen/): 지속적인 개선 마인드셋.
- [**`systematic-debugging`**](../../skills/systematic-debugging/): 전문가처럼 디버깅하기.

---

## 🛡️ 보안 및 컴플라이언스 (Security & Compliance)

### 🛡️ "Security Engineer" 팩
*모의 해킹, 감사 및 시스템 강화를 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`ethical-hacking-methodology`**](../../skills/ethical-hacking-methodology/): 화이트햇 해킹의 바이블.
- [**`burp-suite-testing`**](../../skills/burp-suite-testing/): 웹 취약점 스캐닝.
- [**`top-web-vulnerabilities`**](../../skills/top-web-vulnerabilities/): OWASP 기반 취약점 분류.
- [**`linux-privilege-escalation`**](../../skills/linux-privilege-escalation/): 고급 리눅스 보안 평가.
- [**`cloud-penetration-testing`**](../../skills/cloud-penetration-testing/): AWS/Azure/GCP 보안.
- [**`security-auditor`**](../../skills/security-auditor/): 포괄적인 보안 감사.
- [**`vulnerability-scanner`**](../../skills/vulnerability-scanner/): 고급 취약점 분석.

### 🔐 "Security Developer" 팩
*안전한 애플리케이션 구축을 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`api-security-best-practices`**](../../skills/api-security-best-practices/): 안전한 API 설계 패턴.
- [**`auth-implementation-patterns`**](../../skills/auth-implementation-patterns/): JWT, OAuth2, 세션 관리.
- [**`backend-security-coder`**](../../skills/backend-security-coder/): 안전한 백엔드 코딩 관행.
- [**`frontend-security-coder`**](../../skills/frontend-security-coder/): XSS 방지 및 클라이언트 측 보안.
- [**`cc-skill-security-review`**](../../skills/cc-skill-security-review/): 기능별 보안 체크리스트.
- [**`pci-compliance`**](../../skills/pci-compliance/): 지불 카드 보안 표준.

---

## 🌐 웹 개발 (Web Development)

### 🌐 "Web Wizard" 팩
*현대적이고 고성능의 웹 앱 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`frontend-design`**](../../skills/frontend-design/): UI 가이드라인 및 미학.
- [**`react-best-practices`**](../../skills/react-best-practices/): React & Next.js 성능 최적화.
- [**`react-patterns`**](../../skills/react-patterns/): 현대적 React 패턴 및 원칙.
- [**`nextjs-best-practices`**](../../skills/nextjs-best-practices/): Next.js App Router 패턴.
- [**`tailwind-patterns`**](../../skills/tailwind-patterns/): Tailwind CSS v4 스타일링 초능력.
- [**`form-cro`**](../../skills/form-cro/): 전환율 최적화를 위한 폼 설계.
- [**`seo-audit`**](../../skills/seo-audit/): 구글 검색 상위 노출 전략.

### 🖌️ "Web Designer" 팩
*픽셀 단위의 완벽한 경험을 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`ui-ux-pro-max`**](../../skills/ui-ux-pro-max/): 프리미엄 디자인 시스템 및 토큰.
- [**`frontend-design`**](../../skills/frontend-design/): 디자인 미학의 기초.
- [**`3d-web-experience`**](../../skills/3d-web-experience/): Three.js 및 React Three Fiber 매직.
- [**`canvas-design`**](../../skills/canvas-design/): 정적 비주얼 및 포스터.
- [**`mobile-design`**](../../skills/mobile-design/): 모바일 우선 디자인 원칙.
- [**`scroll-experience`**](../../skills/scroll-experience/): 몰입형 스크롤 기반 경험.

### ⚡ "Full-Stack Developer" 팩
*엔드-투-엔드 웹 애플리케이션 개발용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`senior-fullstack`**](../../skills/senior-fullstack/): 풀스택 개발 전체 가이드.
- [**`frontend-developer`**](../../skills/frontend-developer/): React 19+ 및 Next.js 15+ 전문 지식.
- [**`backend-dev-guidelines`**](../../skills/backend-dev-guidelines/): Node.js/Express/TypeScript 패턴.
- [**`api-patterns`**](../../skills/api-patterns/): REST vs GraphQL vs tRPC 선택.
- [**`database-design`**](../../skills/database-design/): 스키마 설계 및 ORM 선택.
- [**`stripe-integration`**](../../skills/stripe-integration/): 결제 및 구독 구현.

---

## 🤖 AI 및 에이전트 (AI & Agents)

### 🤖 "Agent Architect" 팩
*AI 시스템 및 자율 에이전트 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`agent-evaluation`**](../../skills/agent-evaluation/): 에이전트 테스트 및 벤치마크.
- [**`langgraph`**](../../skills/langgraph/): 상태 기반 에이전트 워크플로우 구축.
- [**`mcp-builder`**](../../skills/mcp-builder/): 나만의 MCP 도구 생성.
- [**`prompt-engineering`**](../../skills/prompt-engineering/): LLM과의 대화 기술 마스터하기.
- [**`ai-agents-architect`**](../../skills/ai-agents-architect/): 자율 AI 에이전트 설계.
- [**`rag-engineer`**](../../skills/rag-engineer/): 벡터 검색을 이용한 RAG 시스템 구축.

### 🧠 "LLM Application Developer" 팩
*운영 환경급 LLM 애플리케이션 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`llm-app-patterns`**](../../skills/llm-app-patterns/): 생산성 높은 LLM 패턴.
- [**`rag-implementation`**](../../skills/rag-implementation/): 검색 증강 생성(RAG) 구현.
- [**`prompt-caching`**](../../skills/prompt-caching/): LLM 프롬프트 캐싱 전략.
- [**`context-window-management`**](../../skills/context-window-management/): LLM 컨텍스트의 효율적 관리.
- [**`langfuse`**](../../skills/langfuse/): LLM 관측성 및 트레이싱.

---

## 🎮 게임 개발 (Game Development)

### 🎮 "Indie Game Dev" 팩
*AI 어시스턴트를 활용한 게임 제작용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`game-development/game-design`**](../../skills/game-development/game-design/): 메커니즘 및 루프 설계.
- [**`game-development/2d-games`**](../../skills/game-development/2d-games/): 스프라이트 및 물리 엔진.
- [**`game-development/3d-games`**](../../skills/game-development/3d-games/): 모델 및 쉐이더.
- [**`unity-developer`**](../../skills/unity-developer/): Unity 6 LTS 개발.
- [**`godot-gdscript-patterns`**](../../skills/godot-gdscript-patterns/): Godot 4 GDScript 패턴.
- [**`algorithmic-art`**](../../skills/algorithmic-art/): 코드로 에셋 생성하기.

---

## 🐍 백엔드 및 언어 (Backend & Languages)

### 🐍 "Python Pro" 팩
*백엔드 전문가 및 데이터 과학자용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`python-pro`**](../../skills/python-pro/): 최신 기능을 갖춘 Python 3.12+ 마스터하기.
- [**`python-patterns`**](../../skills/python-patterns/): 파이썬다운(Idiomatic) 코드 작성.
- [**`fastapi-pro`**](../../skills/fastapi-pro/): 고성능 비동기 API.
- [**`fastapi-templates`**](../../skills/fastapi-templates/): 운영 가능한 FastAPI 프로젝트.
- [**`django-pro`**](../../skills/django-pro/): 강력한 웹 프레임워크 장고.
- [**`python-testing-patterns`**](../../skills/python-testing-patterns/): pytest를 활용한 포괄적 테스트.
- [**`async-python-patterns`**](../../skills/async-python-patterns/): 파이썬 asyncio 마스터하기.

### 🟦 "TypeScript & JavaScript" 팩
*현대적 웹 개발용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`typescript-expert`**](../../skills/typescript-expert/): 타입스크립트 및 고급 타입 마스터하기.
- [**`javascript-pro`**](../../skills/javascript-pro/): ES6+ 기반 현대적 자바스크립트.
- [**`react-best-practices`**](../../skills/react-best-practices/): React 성능 최적화.
- [**`nodejs-best-practices`**](../../skills/nodejs-best-practices/): Node.js 개발 원칙.
- [**`nextjs-app-router-patterns`**](../../skills/nextjs-app-router-patterns/): Next.js 14+ App Router.

### 🦀 "Systems Programming" 팩
*저수준 및 성능 최적화 코드 작성용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`rust-pro`**](../../skills/rust-pro/): 비동기 패턴을 갖춘 Rust 1.75+.
- [**`go-concurrency-patterns`**](../../skills/go-concurrency-patterns/): Go 동시성 마스터하기.
- [**`golang-pro`**](../../skills/golang-pro/): Go 개발 전문 지식.
- [**`memory-safety-patterns`**](../../skills/memory-safety-patterns/): 메모리 안전 프로그래밍.
- [**`cpp-pro`**](../../skills/cpp-pro/): 현대적 C++ 개발.

---

## 🦄 제품 및 비즈니스 (Product & Business)

### 🦄 "Startup Founder" 팩
*단순 코딩을 넘어 제품을 구축하기 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`product-manager-toolkit`**](../../skills/product-manager-toolkit/): RICE 우선순위 설정, PRD 템플릿.
- [**`competitive-landscape`**](../../skills/competitive-landscape/): 경쟁사 분석.
- [**`competitor-alternatives`**](../../skills/competitor-alternatives/): 비교 페이지 생성.
- [**`launch-strategy`**](../../skills/launch-strategy/): 제품 런칭 계획 수립.
- [**`copywriting`**](../../skills/copywriting/): 전환율을 높이는 마케팅 문구.
- [**`stripe-integration`**](../../skills/stripe-integration/): 첫날부터 수익 창출하기.

### 📊 "Business Analyst" 팩
*데이터 기반 의사결정용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`business-analyst`**](../../skills/business-analyst/): AI 기반 분석 및 KPI.
- [**`startup-metrics-framework`**](../../skills/startup-metrics-framework/): SaaS 지표 및 유닛 이코노믹스.
- [**`startup-financial-modeling`**](../../skills/startup-financial-modeling/): 3-5개년 재무 예측.
- [**`market-sizing-analysis`**](../../skills/market-sizing-analysis/): TAM/SAM/SOM 계산.
- [**`kpi-dashboard-design`**](../../skills/kpi-dashboard-design/): 효과적인 KPI 대시보드.

### 📈 "Marketing & Growth" 팩
*사용자 획득 및 유지용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`content-creator`**](../../skills/content-creator/): SEO 최적화 마케팅 콘텐츠.
- [**`seo-audit`**](../../skills/seo-audit/): 기술적 SEO 상태 점검.
- [**`programmatic-seo`**](../../skills/programmatic-seo/): 대규모 페이지 생성 전략.
- [**`analytics-tracking`**](../../skills/analytics-tracking/): GA4/PostHog 올바른 설정.
- [**`ab-test-setup`**](../../skills/ab-test-setup/): 검증된 학습 실험.
- [**`email-sequence`**](../../skills/email-sequence/): 자동 이메일 캠페인.

---

## 🌧️ DevOps 및 인프라 (DevOps & Infrastructure)

### 🌧️ "DevOps & Cloud" 팩
*인프라 구축 및 확장용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`docker-expert`**](../../skills/docker-expert/): 컨테이너 및 멀티스테이지 빌드 마스터하기.
- [**`aws-serverless`**](../../skills/aws-serverless/): AWS 서버리스(Lambda, DynamoDB).
- [**`kubernetes-architect`**](../../skills/kubernetes-architect/): K8s 아키텍처 및 GitOps.
- [**`terraform-specialist`**](../../skills/terraform-specialist/): 코드형 인프라(IaC) 마스터하기.
- [**`environment-setup-guide`**](../../skills/environment-setup-guide/): 팀 표준화 가이드.
- [**`deployment-procedures`**](../../skills/deployment-procedures/): 안전한 롤아웃 전략.
- [**`bash-linux`**](../../skills/bash-linux/): 터미널 마법사가 되는 법.

### 📊 "Observability & Monitoring" 팩
*운영 환경의 안정성 확보용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`observability-engineer`**](../../skills/observability-engineer/): 포괄적인 모니터링 시스템.
- [**`distributed-tracing`**](../../skills/distributed-tracing/): 마이크로서비스 간 요청 추적.
- [**`slo-implementation`**](../../skills/slo-implementation/): 서비스 수준 목표(SLO) 설정.
- [**`incident-responder`**](../../skills/incident-responder/): 신속한 장애 대응.
- [**`postmortem-writing`**](../../skills/postmortem-writing/): 비난 없는 사후 분석 보고서 작성.
- [**`performance-engineer`**](../../skills/performance-engineer/): 애플리케이션 성능 최적화.

---

## 📊 데이터 및 분석 (Data & Analytics)

### 📊 "Data & Analytics" 팩
*숫자에서 의미를 찾아내기 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`analytics-tracking`**](../../skills/analytics-tracking/): GA4/PostHog 올바른 설정.
- [**`claude-d3js-skill`**](../../skills/claude-d3js-skill/): D3.js를 이용한 아름다운 커스텀 시각화.
- [**`sql-pro`**](../../skills/sql-pro/): 클라우드 네이티브 DB와 최신 SQL.
- [**`postgres-best-practices`**](../../skills/postgres-best-practices/): Postgres 최적화.
- [**`ab-test-setup`**](../../skills/ab-test-setup/): 검증된 학습.
- [**`database-architect`**](../../skills/database-architect/): 기초부터 시작하는 데이터베이스 설계.

### 🔄 "Data Engineering" 팩
*데이터 파이프라인 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`data-engineer`**](../../skills/data-engineer/): 데이터 파이프라인 아키텍처.
- [**`airflow-dag-patterns`**](../../skills/airflow-dag-patterns/): Apache Airflow DAG 패턴.
- [**`dbt-transformation-patterns`**](../../skills/dbt-transformation-patterns/): 분석 엔지니어링.
- [**`vector-database-engineer`**](../../skills/vector-database-engineer/): RAG용 벡터 데이터베이스.
- [**`embedding-strategies`**](../../skills/embedding-strategies/): 임베딩 모델 선택 전략.

---

## 🎨 크리에이티브 및 콘텐츠 (Creative & Content)

### 🎨 "Creative Director" 팩
*시각물, 콘텐츠 및 브랜딩용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`canvas-design`**](../../skills/canvas-design/): 포스터 및 다이어그램 생성.
- [**`frontend-design`**](../../skills/frontend-design/): UI 미학.
- [**`content-creator`**](../../skills/content-creator/): SEO 최적화 블로그 포스트.
- [**`copy-editing`**](../../skills/copy-editing/): 매끄러운 문장 다듬기.
- [**`algorithmic-art`**](../../skills/algorithmic-art/): 코드로 생성하는 예술 작품.
- [**`interactive-portfolio`**](../../skills/interactive-portfolio/): 취업을 부르는 포트폴리오.

---

## 🐞 품질 보증 (Quality Assurance)

### 🐞 "QA & Testing" 팩
*사용자보다 먼저 문제점을 발견하기 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`test-driven-development`**](../../skills/test-driven-development/): Red, Green, Refactor.
- [**`systematic-debugging`**](../../skills/systematic-debugging/): 셜록 홈즈처럼 디버깅하기.
- [**`browser-automation`**](../../skills/browser-automation/): Playwright를 이용한 E2E 테스트.
- [**`e2e-testing-patterns`**](../../skills/e2e-testing-patterns/): 신뢰할 수 있는 E2E 테스트 스위트.
- [**`ab-test-setup`**](../../skills/ab-test-setup/): 검증된 실험.
- [**`code-review-checklist`**](../../skills/code-review-checklist/): PR에서 버그 잡아내기.
- [**`test-fixing`**](../../skills/test-fixing/): 실패한 테스트의 체계적 수정.

---

## 🔧 전문화 팩 (Specialized Packs)

### 📱 "Mobile Developer" 팩
*iOS, Android 및 크로스 플랫폼 앱용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`mobile-developer`**](../../skills/mobile-developer/): 크로스 플랫폼 모바일 개발.
- [**`react-native-architecture`**](../../skills/react-native-architecture/): Expo 기반 React Native.
- [**`flutter-expert`**](../../skills/flutter-expert/): Flutter 멀티 플랫폼 앱.
- [**`ios-developer`**](../../skills/ios-developer/): Swift 기반 iOS 개발.
- [**`app-store-optimization`**](../../skills/app-store-optimization/): 앱스토어 및 플레이스토어 ASO.

### 🔗 "Integration & APIs" 팩
*서비스 연결 및 통합 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`stripe-integration`**](../../skills/stripe-integration/): 결제 및 구독.
- [**`twilio-communications`**](../../skills/twilio-communications/): SMS, 음성, WhatsApp.
- [**`hubspot-integration`**](../../skills/hubspot-integration/): CRM 통합.
- [**`plaid-fintech`**](../../skills/plaid-fintech/): 은행 계좌 연결 및 ACH.
- [**`algolia-search`**](../../skills/algolia-search/): 검색 엔진 구현.

### 🎯 "Architecture & Design" 팩
*시스템 설계 및 기술적 의사결정용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`senior-architect`**](../../skills/senior-architect/): 포괄적인 소프트웨어 아키텍처.
- [**`architecture-patterns`**](../../skills/architecture-patterns/): 클린 아키텍처, DDD, 헥사고날.
- [**`microservices-patterns`**](../../skills/microservices-patterns/): 마이크로서비스 아키텍처.
- [**`event-sourcing-architect`**](../../skills/event-sourcing-architect/): 이벤트 소싱 및 CQRS.
- [**`architecture-decision-records`**](../../skills/architecture-decision-records/): 기술 결정 사항 문서화.

### 🧱 "DDD & Evented Architecture" 팩
*복잡한 도메인 모델링 및 이벤트 기반 시스템으로의 진화를 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`domain-driven-design`**](../../skills/domain-driven-design/): 전략적 모델링부터 구현 패턴까지 DDD 워크플로우 가이드.
- [**`ddd-strategic-design`**](../../skills/ddd-strategic-design/): 서브도메인, 바운디드 컨텍스트, 보편 언어(Ubiquitous Language).
- [**`ddd-context-mapping`**](../../skills/ddd-context-mapping/): 컨텍스트 간 통합 및 부패 방지 계층(ACL).
- [**`ddd-tactical-patterns`**](../../skills/ddd-tactical-patterns/): 애그리거트, 값 객체, 레포지토리, 도메인 이벤트.
- [**`cqrs-implementation`**](../../skills/cqrs-implementation/): 읽기/쓰기 모델 분리.
- [**`event-store-design`**](../../skills/event-store-design/): 이벤트 영속성 및 재생 아키텍처.
- [**`saga-orchestration`**](../../skills/saga-orchestration/): 컨텍스트 간 장기 실행 트랜잭션 조정.
- [**`projection-patterns`**](../../skills/projection-patterns/): 이벤트 스트림으로부터 구체화된 읽기 모델 생성.

### 🤖 "Automation Builder" 팩
*도구 연결 및 반복 가능한 자동화 워크플로우 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`workflow-automation`**](../../skills/workflow-automation/): AI 및 비즈니스 시스템을 위한 견고한 자동화 흐름 설계.
- [**`mcp-builder`**](../../skills/mcp-builder/): 에이전트가 신뢰하고 사용할 수 있는 도구 인터페이스 생성.
- [**`make-automation`**](../../skills/make-automation/): Make/Integromat 기반 자동화 구축.
- [**`airtable-automation`**](../../skills/airtable-automation/): 에어테이블 레코드, 베이스, 뷰 자동화.
- [**`notion-automation`**](../../skills/notion-automation/): 노션 페이지, 데이터베이스, 블록 자동화.
- [**`slack-automation`**](../../skills/slack-automation/): 슬랙 메시징 및 채널 워크플로우 자동화.
- [**`googlesheets-automation`**](../../skills/googlesheets-automation/): 스프레드시트 업데이트 및 데이터 작업 자동화.

### 💼 "RevOps & CRM Automation" 팩
*수익 관리(RevOps), 지원 업무 연동 및 CRM 중심 자동화용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`hubspot-automation`**](../../skills/hubspot-automation/): 연락처, 회사, 거래, 티켓 자동화.
- [**`sendgrid-automation`**](../../skills/sendgrid-automation/): 이메일 발송, 연락처, 템플릿 자동화.
- [**`zendesk-automation`**](../../skills/zendesk-automation/): 지원 티켓 및 답변 워크플로우 자동화.
- [**`google-calendar-automation`**](../../skills/google-calendar-automation/): 일정 예약 및 가용성 관리.
- [**`outlook-calendar-automation`**](../../skills/outlook-calendar-automation/): 아웃룩 미팅 및 초대 자동화.
- [**`stripe-automation`**](../../skills/stripe-automation/): 청구, 송장, 구독 자동화.
- [**`shopify-automation`**](../../skills/shopify-automation/): 제품, 주문, 고객, 재고 자동화.

### 💳 "Commerce & Payments" 팩
*수익화, 결제 및 커머스 워크플로우용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`stripe-integration`**](../../skills/stripe-integration/): 견고한 체크아웃, 구독 및 웹훅 흐름 구축.
- [**`paypal-integration`**](../../skills/paypal-integration/): 페이팔 결제 및 관련 흐름 통합.
- [**`plaid-fintech`**](../../skills/plaid-fintech/): 은행 계좌 연결 및 ACH 관련 케이스 처리.
- [**`hubspot-integration`**](../../skills/hubspot-integration/): CRM 데이터를 제품 및 수익 워크플로우에 연결.
- [**`algolia-search`**](../../skills/algolia-search/): 커머스 경험에 검색 및 발견 기능 추가.
- [**`monetization`**](../../skills/monetization/): 의도적인 가격 책정 및 수익화 시스템 설계.

### 🏢 "Odoo ERP" 팩
*Odoo 기반 비즈니스 시스템을 구축하거나 운영하는 팀용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`odoo-module-developer`**](../../skills/odoo-module-developer/): 깔끔한 커스텀 Odoo 모듈 생성.
- [**`odoo-orm-expert`**](../../skills/odoo-orm-expert/): Odoo ORM 패턴 및 성능 활용.
- [**`odoo-sales-crm-expert`**](../../skills/odoo-sales-crm-expert/): 영업 파이프라인, 리드 및 예측 최적화.
- [**`odoo-ecommerce-configurator`**](../../skills/odoo-ecommerce-configurator/): 쇼핑몰, 카탈로그, 주문 흐름 설정.
- [**`odoo-performance-tuner`**](../../skills/odoo-performance-tuner/): 느린 Odoo 인스턴스 진단 및 개선.
- [**`odoo-security-rules`**](../../skills/odoo-security-rules/): 안전한 접근 제어 및 규칙 설계 적용.
- [**`odoo-docker-deployment`**](../../skills/odoo-docker-deployment/): Docker 기반 환경에서 Odoo 배포 및 실행.

### ☁️ "Azure AI & Cloud" 팩
*클라우드, AI 및 플랫폼 서비스 전반에 걸친 Azure 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`azd-deployment`**](../../skills/azd-deployment/): Azure Developer CLI 워크플로우로 Azure 앱 배포.
- [**`azure-functions`**](../../skills/azure-functions/): Azure Functions를 이용한 서버리스 작업 구축.
- [**`azure-ai-openai-dotnet`**](../../skills/azure-ai-openai-dotnet/): .NET 애플리케이션에서 Azure OpenAI 사용.
- [**`azure-search-documents-py`**](../../skills/azure-search-documents-py/): 파이썬 기반 검색, 하이브리드 검색 및 인덱싱 구축.
- [**`azure-identity-py`**](../../skills/azure-identity-py/): 파이썬 서비스의 Azure 인증 흐름 처리.
- [**`azure-monitor-opentelemetry-ts`**](../../skills/azure-monitor-opentelemetry-ts/): 타입스크립트 앱의 텔레메트리 및 추적 기능 추가.

### 📲 "Expo & React Native" 팩
*Expo 및 React Native 기반 모바일 앱 배포용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`react-native-architecture`**](../../skills/react-native-architecture/): 운영 환경급 React Native 앱의 구조 설계.
- [**`expo-api-routes`**](../../skills/expo-api-routes/): Expo Router 및 EAS Hosting 기반 API 라우트 구축.
- [**`expo-dev-client`**](../../skills/expo-dev-client/): Expo 개발 클라이언트 빌드 및 배포.
- [**`expo-tailwind-setup`**](../../skills/expo-tailwind-setup/): Expo 앱의 Tailwind 및 NativeWind 설정.
- [**`expo-cicd-workflows`**](../../skills/expo-cicd-workflows/): EAS 워크플로우를 이용한 빌드 및 릴리즈 자동화.
- [**`expo-deployment`**](../../skills/expo-deployment/): Expo 앱 배포 및 릴리즈 흐름 관리.
- [**`app-store-optimization`**](../../skills/app-store-optimization/): 앱스토어 및 플레이스토어 발견 가능성 향상.

### 🍎 "Apple Platform Design" 팩
*애플 플랫폼 네이티브 경험을 설계하는 팀용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`hig-foundations`**](../../skills/hig-foundations/): Apple Human Interface Guidelines 핵심 원칙 학습.
- [**`hig-patterns`**](../../skills/hig-patterns/): 애플 상호작용 및 UX 패턴의 올바른 적용.
- [**`hig-components-layout`**](../../skills/hig-components-layout/): 애플 레이아웃 및 내비게이션 컴포넌트의 활용.
- [**`hig-inputs`**](../../skills/hig-inputs/): 제스처, 키보드, Pencil, 포커스 및 컨트롤러 설계.
- [**`hig-components-system`**](../../skills/hig-components-system/): 위젯, 라이브 액티비티 및 시스템 서페이스 작업.
- [**`hig-platforms`**](../../skills/hig-platforms/): 애플 기기 제품군 전반에 걸친 경험 최적화.

### 🧩 "Makepad Builder" 팩
*Makepad 생태계를 이용한 UI 중심 앱 구축용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`makepad-basics`**](../../skills/makepad-basics/): Makepad 기초 및 멘탈 모델 이해.
- [**`makepad-layout`**](../../skills/makepad-layout/): 크기 조절, 흐름, 정렬 및 레이아웃 구성 처리.
- [**`makepad-widgets`**](../../skills/makepad-widgets/): Makepad 위젯으로 인터페이스 구축.
- [**`makepad-event-action`**](../../skills/makepad-event-action/): 상호작용 및 이벤트 처리 연결.
- [**`makepad-shaders`**](../../skills/makepad-shaders/): GPU 기반 시각 효과 및 커스텀 드로잉 생성.
- [**`makepad-deployment`**](../../skills/makepad-deployment/): Makepad 프로젝트 패키징 및 배포.

### 🔎 "SEO Specialist" 팩
*기술적 SEO, 콘텐츠 구조 및 검색 기반 성장용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`seo-fundamentals`**](../../skills/seo-fundamentals/): 탄탄한 SEO 원칙 및 검색 제약 조건을 기반으로 구축.
- [**`seo-content-planner`**](../../skills/seo-content-planner/): 클러스터, 캘린더 및 콘텐츠 갭 계획 수립.
- [**`seo-content-writer`**](../../skills/seo-content-writer/): 의도와 일치하는 검색 친화적 콘텐츠 초안 작성.
- [**`seo-structure-architect`**](../../skills/seo-structure-architect/): 계층 구조, 내부 링크 및 구조 개선.
- [**`seo-cannibalization-detector`**](../../skills/seo-cannibalization-detector/): 동일한 키워드로 경쟁하는 중복 페이지 탐색.
- [**`seo-content-auditor`**](../../skills/seo-content-auditor/) : 기존 콘텐츠 품질 및 최적화 공백 감사.
- [**`schema-markup`**](../../skills/schema-markup/): 풍부한 검색 결과를 위한 구조화된 데이터 추가.

### 📄 "Documents & Presentations" 팩
*문서 중심 워크플로우, 스프레드시트, PDF 및 발표 자료용.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`office-productivity`**](../../skills/office-productivity/): 문서, 스프레드시트 및 프레젠테이션 워크플로우 조정.
- [**`docx-official`**](../../skills/docx-official/): 워드 호환 문서 생성 및 편집.
- [**`pptx-official`**](../../skills/pptx-official/): 파워포인트 호환 발표 자료 생성 및 편집.
- [**`xlsx-official`**](../../skills/xlsx-official/): 수식과 서식을 갖춘 스프레드시트 생성 및 분석.
- [**`pdf-official`**](../../skills/pdf-official/): 프로그래밍 방식으로 PDF 추출, 생성 및 조작.
- [**`google-slides-automation`**](../../skills/google-slides-automation/): 구글 슬라이드 업데이트 자동화.
- [**`google-sheets-automation`**](../../skills/google-sheets-automation/): 구글 시트 읽기 및 쓰기 자동화.

---

## 🧰 메인테이너 및 오픈소스 (Maintainer & OSS)

### 🛠️ "OSS Maintainer" 팩
*공개 저장소에서 깔끔한 변경 사항을 배포하기 위한 번들.*

**플러그인 상태:** Codex 플러그인 안전 · Claude 플러그인 안전

- [**`commit`**](../../skills/commit/): 고품질의 컨벤셔널 커밋 작성.
- [**`create-pr`**](../../skills/create-pr/): 리뷰 준비가 된 컨텍스트를 갖춘 PR 생성.
- [**`requesting-code-review`**](../../skills/requesting-code-review/): 명확하고 고신호(High-signal)의 리뷰 요청.
- [**`receiving-code-review`**](../../skills/receiving-code-review/): 기술적 엄격함을 바탕으로 피드백 적용.
- [**`changelog-automation`**](../../skills/changelog-automation/): 릴리즈 노트 및 변경 이력의 일관성 유지.
- [**`git-advanced-workflows`**](../../skills/git-advanced-workflows/): Rebase, cherry-pick, bisect, 복구 작업.
- [**`documentation-templates`**](../../skills/documentation-templates/): 문서 및 인수인계 표준화.

### 🧱 "Skill Author" 팩
*고품질의 SKILL.md 에셋 제작 및 유지보수용.*

**플러그인 상태:** Codex 검증 중 · Claude 검증 중

- [**`skill-creator`**](../../skills/skill-creator/): 효과적인 새로운 스킬 설계.
- [**`skill-developer`**](../../skills/skill-developer/): 트리거, 훅 및 스킬 라이프사이클 구현.
- [**`writing-skills`**](../../skills/writing-skills/): 스킬 지침의 명확성 및 구조 개선.
- [**`documentation-generation-doc-generate`**](../../skills/documentation-generation-doc-generate/): 유지보수 가능한 기술 문서 생성.
- [**`lint-and-validate`**](../../skills/lint-and-validate/): 편집 후 품질 검증.
- [**`verification-before-completion`**](../../skills/verification-before-completion/): 완료 선언 전 변경 사항 최종 확인.

---

## 📚 번들 활용 가이드

### 1) 즉각적인 목표에 따라 선택하기

- 지금 당장 기능을 배포해야 함: `Essentials` + 도메인 팩 하나 (`Web Wizard`, `Python Pro`, `DevOps & Cloud` 등).
- 안정성 및 강화가 필요함: `QA & Testing` + `Security Developer` 추가.
- 제품 성장이 필요함: `Startup Founder` 또는 `Marketing & Growth` 추가.

### 2) 20개가 아닌 3~5개의 스킬로 시작하기

현재 마일스톤에 필요한 최소한의 세트만 선택하세요. 실제 부족함을 느낄 때만 확장하는 것이 효율적입니다.

### 3) 일관된 스킬 호출

- **Claude Code**: 번들 플러그인 설치 또는 `>> /스킬이름 도움말...` 사용
- **Codex CLI**: 마켓플레이스에서 번들 플러그인 설치 또는 `Use 스킬이름...` 사용
- **Cursor**: 채팅창에서 `@스킬이름` 참조
- **Gemini CLI**: `Use 스킬이름...` 사용

### 4) 나만의 단축 리스트 만들기

자주 사용하는 스킬들로 작은 리스트를 만들어 작업 전반에 재사용하면 컨텍스트 스위칭을 줄일 수 있습니다.

---

## 🧩 추천 번들 조합

### SaaS MVP 배포 (2주 소요)
`Essentials` + `Full-Stack Developer` + `QA & Testing` + `Startup Founder`

### 기존 운영 앱 강화
`Essentials` + `Security Developer` + `DevOps & Cloud` + `Observability & Monitoring`

### AI 제품 구축
`Essentials` + `Agent Architect` + `LLM Application Developer` + `Data Engineering`

### 트래픽 및 전환율 성장
`Web Wizard` + `Marketing & Growth` + `Data & Analytics`

### 오픈소스 출시 및 유지보수
`Essentials` + `OSS Maintainer` + `Architecture & Design`

---

## 📚 학습 경로 (Learning Paths)

### 초급 → 중급 → 고급

**웹 개발:**
1. 시작: `Essentials` → `Web Wizard`
2. 성장: `Full-Stack Developer` → `Architecture & Design`
3. 마스터: `Observability & Monitoring` → `Security Developer`

**AI/ML:**
1. 시작: `Essentials` → `Agent Architect`
2. 성장: `LLM Application Developer` → `Data Engineering`
3. 마스터: 고급 RAG 및 에이전트 오케스트레이션

**보안:**
1. 시작: `Essentials` → `Security Developer`
2. 성장: `Security Engineer` → 고급 모의 해킹
3. 마스터: 레드팀 전술 및 위협 모델링

**오픈소스 메인테이너:**
1. 시작: `Essentials` → `OSS Maintainer`
2. 성장: `Architecture & Design` → `QA & Testing`
3. 마스터: `Skill Author` + 릴리즈 자동화 워크플로우

---

## 기여하기

번들에 포함되어야 할 스킬을 발견했거나 새로운 번들을 만들고 싶으신가요? [Issue를 생성](https://github.com/sickn33/antigravity-awesome-skills/issues)하거나 PR을 보내주세요!

---

## 관련 문서

- [시작 가이드](GETTING_STARTED.ko.md)
- [전체 스킬 카탈로그](../../CATALOG.md)
- [기여 가이드](../../CONTRIBUTING.md)

---

_최종 업데이트: 2026년 3월 | 총 스킬 수: 1,445+ | 총 번들 수: 37_
