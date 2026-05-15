Create a GitHub Actions workflow that runs as part of the imported daily repository status process. The workflow should:
- run on `workflow_dispatch`
- use `ubuntu-latest`
- collect repository status information such as latest commit, open issues, open pull requests, and current branch info
- save the report as an artifact or print it to the workflow logs
- include a job named `daily_repo_status`
