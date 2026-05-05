# 🌌 Antigravity Awesome Skills: Claude Code, Gemini CLI, Cursor 등을 위한 1,445개 이상의 에이전트 스킬

> **Claude Code, Cursor, Codex CLI, Gemini CLI, Antigravity 및 기타 AI 코딩 어시스턴트를 위한 1,445개 이상의 에이전트 스킬을 담은 설치 가능한 GitHub 라이브러리입니다.**

Antigravity Awesome Skills는 재사용 가능한 `SKILL.md` 플레이북을 위한 설치 가능한 GitHub 라이브러리이자 npm 설치 프로그램입니다. 이 프로젝트는 구조화된 운영 지침이 필요한 Claude Code, Cursor, Codex CLI, Gemini CLI, Antigravity, Kiro, OpenCode, GitHub Copilot 및 기타 AI 코딩 어시스턴트를 위해 설계되었습니다. 단순한 프롬프트 조각을 모으는 대신, 이 저장소는 검색 및 설치가 가능한 스킬 카탈로그, 번들, 워크플로우, 플러그인 안전 배포판 및 실용적인 문서를 제공하여 AI 에이전트가 더 나은 컨텍스트, 강력한 제약 조건 및 명확한 출력을 가지고 반복적인 작업을 수행할 수 있도록 돕습니다.

이 저장소를 사용하여 광범위한 멀티 툴 스킬 라이브러리를 설치하거나, 역할 기반 번들로 시작하거나, 계획, 코딩, 디버깅, 테스트, 보안 검토, 인프라, 제품 작업 및 성장 작업을 위한 워크플로우 중심 실행으로 바로 뛰어들 수 있습니다.

**여기서 시작하세요:** [저장소 스타(Star) 하기](https://github.com/sickn33/antigravity-awesome-skills/stargazers) · [1분 만에 설치하기](#설치-방법) · [도구 선택하기](#도구-선택) · [도구별 최적의 스킬](#도구별-최적의-스킬) · [📚 1,445개 이상의 스킬 찾아보기](../../CATALOG.md) · [번들](BUNDLES.ko.md) · [워크플로우](WORKFLOWS.ko.md) · [자주 묻는 질문(FAQ)](FAQ.ko.md) · [Windows 경로 오류 해결](WINDOWS_RECOVERY.ko.md)

---

## 왜 이 저장소를 사용해야 하나요?

- **단순한 영감이 아닌 설치 가능한 도구**: `npx antigravity-awesome-skills`를 사용하여 도구가 기대하는 위치에 스킬을 즉시 배치할 수 있습니다.
- **주요 에이전트 워크플로우에 최적화**: Claude Code, Cursor, Codex CLI, Gemini CLI, Antigravity, Kiro, OpenCode, Copilot 등에서 바로 사용 가능합니다.
- **광범위하고 실용적인 범위**: 개발, 테스트, 보안, 인프라, 제품 및 마케팅 전반에 걸친 1,445개 이상의 스킬을 보유하고 있습니다.
- **빠른 온보딩**: 번들과 워크플로우를 통해 저장소를 발견한 시점부터 첫 스킬을 사용하는 시점까지의 시간을 단축해 줍니다.

## 설치 방법

대부분의 사용자는 전체 라이브러리 설치로 시작한 다음, 번들이나 워크플로우를 사용하여 먼저 시도해 볼 것을 좁혀가는 것이 좋습니다.

### 전체 라이브러리 설치

```bash
# 기본값: ~/.gemini/antigravity/skills (Antigravity 글로벌). 다른 위치는 --path를 사용하세요.
npx antigravity-awesome-skills
```

### 설치 확인

```bash
test -d ~/.gemini/antigravity/skills && echo "Skills installed in ~/.gemini/antigravity/skills"
```

### 첫 번째 스킬 실행하기

```text
@brainstorming을 사용하여 SaaS MVP를 계획해 줘.
```

## 도구 선택

동일한 저장소를 사용하되, 각 도구가 기대하는 방식대로 설치하거나 호출하세요.

| 도구 | 설치 방법 | 첫 사용 예시 |
| :--- | :--- | :--- |
| **Claude Code** | `npx antigravity-awesome-skills --claude` | `>> /brainstorming 기능을 계획해 줘` |
| **Cursor** | `npx antigravity-awesome-skills --cursor` | `@brainstorming 기능을 계획해 줘` |
| **Gemini CLI** | `npx antigravity-awesome-skills --gemini` | `Use brainstorming to plan a feature` |
| **Antigravity** | `npx antigravity-awesome-skills --antigravity` | `Use @brainstorming을 사용하여 기능을 계획해 줘` |

## 도구별 가이드
- [Claude Code용 가이드](CLAUDE_CODE_SKILLS.ko.md)
- [Cursor용 가이드](CURSOR_SKILLS.ko.md)
- [Gemini CLI 및 기타 도구](USAGE.ko.md)

## 유니버설 스타터 스킬

- `@brainstorming`: 구현 전 계획 수립용.
- `@test-driven-development`: TDD 중심 작업용.
- `@debugging-strategies`: 체계적인 문제 해결용.
- `@lint-and-validate`: 가벼운 품질 검사용.
- `@security-auditor`: 보안 중심 검토용.
- `@frontend-design`: UI 및 상호작용 품질 향상용.
- `@api-design-principles`: API 형태 및 일관성 유지용.
- `@create-pr`: 작업을 깔끔한 Pull Request로 패키징하는 용도.

## 기여하기

- `skills/<skill-name>/SKILL.md` 아래에 새로운 스킬을 추가하세요.
- 기여자 가이드인 [`CONTRIBUTING.md`](../../CONTRIBUTING.md)를 따르세요.
- PR을 올리기 전에 `npm run validate`로 검증하세요.
