# Claude Code용 Antigravity 스킬 사용 가이드

Claude Code 터미널 환경에서 Antigravity 스킬을 최대한 활용하는 방법입니다.

## 기본 호출 방법

Claude Code에서는 `/view` 명령어나 일반 채팅을 통해 스킬을 호출할 수 있습니다.

```bash
# 특정 스킬의 지침을 읽고 실행하도록 지시
Read the instructions in skills/concise-planning/SKILL.md and help me plan my next task.

# 또는 짧게 스킬 이름을 언급
Use @concise-planning to create a task list.
```

## 최적화된 활용 팁

1. **컨텍스트 로드**: 작업 시작 시 필요한 스킬 파일들을 먼저 `view_file` 도구로 읽게 하는 것이 좋습니다.
2. **복합 호출**: "Use @brainstorming for design and then @concise-planning for the task list"와 같이 여러 스킬을 연쇄적으로 지시할 수 있습니다.
3. **로컬 설정**: `~/.claudecode/config.json`에 Antigravity 스킬 경로를 추가하여 더 빠르게 접근하게 할 수도 있습니다.

---
추가 정보는 [USAGE.ko.md](USAGE.ko.md)를 참조하세요.
