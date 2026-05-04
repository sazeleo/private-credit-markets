# Claude Code Operating Rules

Work in small commits.

Before editing:
- inspect only the necessary files
- propose a commit-sized plan
- tell me which files you will touch

Do not:
- read the whole repo unless necessary
- modify .env, secrets, auth, payments, database migrations, Docker, deploy config, or package versions without approval
- install packages without approval
- delete files without approval
- commit or push without approval

After each chunk:
- summarize changed files
- show git diff summary
- suggest commit message
- ask before committing
- ask before pushing

Use subagents for exploration, docs, tests, and summaries.
Keep main context small.