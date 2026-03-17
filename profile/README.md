# ink-dojo

Building **InkWeave** — a notes-first AI structuring tool for knowledge workers who think in multiple languages.

---

### What we're working on

**InkWeave** is an Obsidian-class editor with Granola-class audio integration — built for scientists, engineers, and knowledge workers in bilingual environments.

```
Your notes + meeting transcript → Claude → structured Markdown document
```

Every existing meeting tool is locked to its own ecosystem — 飞书 only records 飞书, 腾讯会议 only records 腾讯会议. Chinese professionals average 3–5 platforms per day. InkWeave captures from all of them.

---

### Stack

- **Frontend** — Next.js + TypeScript, Vditor editor
- **Desktop** — Tauri (macOS + Windows, coming in Phase 3)
- **Backend** — FastAPI (Python)
- **AI** — Anthropic Claude for structuring, Whisper for ASR
- **DB** — SQLite

---

### Roadmap

| Phase | Status | Goal |
|---|---|---|
| 1 — Editor + Text MVP | 🔨 In progress | Prove structuring pipeline |
| 2 — Audio + Multi-template | Planned | Notes + transcript synthesis |
| 3 — Desktop App | Planned | Silent system audio capture, cross-platform |
| 4 — Ecosystem + Mobile | Planned | Export to 飞书 / 钉钉 / GitHub / mobile |

---

*Private alpha. More soon.*
