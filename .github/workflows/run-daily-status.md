---
on:
  workflow_dispatch:

imports:
  - ./daily-repo-status.md

engine:
  id: codex
  env:
    OPENAI_BASE_URL: https://openrouter.ai/api/v1
    OPENAI_API_KEY: ${{ secrets.OPENAI_API_KEY }}
---

Generate a daily repository status report.