---
on:
  workflow_dispatch:
  schedule:
    - cron: 'daily'

imports:
  - daily-repo-status.md
---

# Run Daily Status

Execute the imported workflow and generate a repository status summary.

Include:
- Open pull requests
- Failed workflows
- Recent commits
- Issues needing attention