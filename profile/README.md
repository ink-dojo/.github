# ink-dojo

Building **InkWeave** — an AI-powered note structuring tool for knowledge workers who think in multiple languages.

---

### What we're building

**InkWeave** turns raw input into structured Markdown documents — instantly.

```
handwritten notes / meeting recording / uploaded PDF / typed text
              ↓  Claude + Whisper
        structured Markdown document
```

Every existing meeting tool is locked to its own ecosystem — 飞书 only works in 飞书, Zoom only in Zoom. Chinese professionals use 3–5 platforms daily. InkWeave works with all of them.

---

### Current status

- ✅ Text / image / audio / PDF input → structured output
- ✅ Real-time recording + live transcription
- ✅ Speaker diarization (who said what)
- ✅ User auth + project management
- ✅ Desktop app skeleton (Tauri)
- 🚧 Deployment & first real users

---

### Stack

| Layer | Tech |
|---|---|
| Frontend | Next.js + TypeScript, Vditor editor |
| Desktop | Tauri (macOS + Windows) |
| Backend | FastAPI (Python) |
| AI | Claude (structuring) + Whisper (ASR) |
| DB | SQLite + SQLAlchemy |

---

### Roadmap

| Phase | Status | Goal |
|---|---|---|
| 1 — Editor MVP | ✅ Done | Text → structured Markdown |
| 2 — Audio + Recording | ✅ Done | Live transcription + speaker ID |
| 3 — Production | 🚧 Now | Deploy, auth, first 5 users |
| 4 — Desktop App | Planned | Silent audio capture, offline mode |
| 5 — Ecosystem | Planned | 飞书 / 钉钉 / GitHub export, mobile |

---

*Private alpha — Columbia University, 2026*
