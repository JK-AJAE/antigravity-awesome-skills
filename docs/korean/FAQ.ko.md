# 자주 묻는 질문 (FAQ)

Antigravity Awesome Skills 사용 중 궁금할 수 있는 내용들을 정리했습니다.

### Q: Antigravity Awesome Skills가 정확히 무엇인가요?
**A:** Claude Code, Cursor, Gemini CLI 등 AI 코딩 어시스턴트들이 더 똑똑하게 일할 수 있도록 도와주는 **'지침서(Skill)'들의 모음집**입니다. 1,400개 이상의 전문적인 작업 지침이 들어있는 거대한 도구 상자라고 생각하시면 됩니다.

### Q: 어떻게 설치하나요?
**A:** 터미널에서 `npx antigravity-awesome-skills`를 실행하는 것이 가장 빠르고 쉽습니다. 특정 도구용으로 설치하려면 `--cursor`, `--claude` 등의 플래그를 붙일 수 있습니다.

### Q: 스킬을 어떻게 호출하나요?
**A:** AI와 대화할 때 `@스킬이름` 형식을 사용하면 됩니다. 
예: `@brainstorming 기능을 설계해 줘.`

### Q: 모든 스킬을 다 설치하면 AI가 느려지거나 헷갈려 하지 않나요?
**A:** 파일이 로컬에 저장되어 있다고 해서 AI가 한꺼번에 모든 파일을 읽는 것은 아닙니다. 여러분이 특정 스킬을 호출할 때만 해당 내용을 읽으므로 성능 걱정은 하지 않으셔도 됩니다.

### Q: 나만의 스킬을 직접 추가할 수도 있나요?
**A:** 물론입니다! `skills/` 폴더 아래에 새로운 폴더를 만들고 `SKILL.md` 파일을 작성하면 됩니다. **@skill-creator** 스킬을 사용하면 AI가 여러분의 새로운 스킬 작성을 도와줍니다.

### Q: Windows에서 경로가 너무 길다는 에러가 납니다.
**A:** Windows의 파일 경로 길이 제한(260자) 때문에 발생할 수 있습니다. [Windows Truncation Recovery](../users/windows-truncation-recovery.md) 문서를 참조하여 설정을 변경하거나 설치 경로를 짧게 조정해 보세요.

---

더 궁금한 점이 있으시면 [GitHub Discussions](https://github.com/sickn33/antigravity-awesome-skills/discussions)에 질문을 남겨주세요!
