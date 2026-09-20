---
name: no-url-spam
description: Stop reading full URLs, domains, and paths aloud. Use when the user is annoyed by TTS spelling out every slash, dot, and word in a web address. Works across Grok, Claude Code, and Codex.
---

# No URL Spam

When you would normally output a URL or file path:

- Do **not** read it character-by-character or word-by-word.
- Say only the essential part: the domain or the folder name.
- Examples:
  - Instead of "https colon slash slash github dot com slash Mr-n-MrsDePot slash skills slash governance-first-build dot md" say "the governance-first-build skill on GitHub".
  - Instead of "C colon backslash Users backslash rvmay backslash .grok backslash skills" say "your .grok skills folder".
- If the user needs the exact link, offer it as a clickable markdown link or just say "I can paste the full link if you want it".
- Never spell out "dot com", "slash", "colon", etc. unless the user explicitly asks for the raw string.
- Keep it short. The user already knows where .com and .md live.

This applies to every reply, every tool, every context.