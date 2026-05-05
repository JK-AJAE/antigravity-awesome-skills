# Cursor용 Antigravity 스킬 사용 가이드

Cursor의 강력한 AI 기능과 Antigravity 스킬 라이브러리를 결합하는 방법입니다.

## 설정 방법

Cursor 설정(`Ctrl+Shift+J`)에서 다음 단계를 수행하세요:

1. **Features** > **Rules for AI** 섹션으로 이동합니다.
2. Antigravity의 핵심 스킬 내용(예: `skills/concise-planning/SKILL.md`)을 복사하여 붙여넣거나, 해당 파일들을 프로젝트의 `.cursorrules` 파일에 링크합니다.

## 프로젝트별 .cursorrules 활용

가장 추천하는 방법은 프로젝트 루트에 `.cursorrules` 파일을 만들고 자주 사용하는 스킬들을 정의하는 것입니다.

```markdown
# .cursorrules 예시
Always follow the patterns in skills/frontend-design/SKILL.md for UI work.
When debugging, use the workflow defined in skills/systematic-debugging/SKILL.md.
```

## @ 기호 활용

Cursor 채팅창이나 `Ctrl+K` 프롬프트에서 `@Files`를 사용하여 특정 스킬 파일을 직접 참조할 수 있습니다.

예: `@SKILL.md (in concise-planning) 이 지침에 따라 오늘 작업 목록을 만들어 줘.`

---
추가 정보는 [USAGE.ko.md](USAGE.ko.md)를 참조하세요.
