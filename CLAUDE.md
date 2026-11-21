# 작업 메모

- 스킬은 `.claude/skills/` 에 저장한다 (prompt-master, humanizer, save-as-skill).
- 사용자가 "방금 한 방식을 스킬로 만들어줘" / "이거 스킬로 저장해줘"라고 하면 `save-as-skill` 스킬을 사용해 `.claude/skills/<이름>/SKILL.md`로 저장하고 커밋·푸시한다.
- 한국어 글을 다듬어 달라고 하면 `humanizer` 스킬을 쓰고 `references/korean.md`를 함께 적용한다.
- 직무 플러그인: marketing@knowledge-work-plugins (`.claude/settings.json`에서 활성화).
