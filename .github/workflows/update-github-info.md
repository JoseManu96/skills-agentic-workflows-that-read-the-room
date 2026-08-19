---
name: update-github-info
description: Draft website updates for Mona's GitHub Info site from official GitHub sources.
on:
  workflow_dispatch:
  schedule:
    - cron: '17 9 * * *'
tools:
  edit:
  web-fetch:
safe-outputs:
  create-pull-request:
    title-prefix: "[mona] "
    draft: true
    fallback-as-issue: false
network:
  allowed:
    - github.com
    - github.blog
    - awesome-copilot.github.com
---

# Update Mona's GitHub Info website

Read `notes/mona-notes.md` before drafting any changes.

Use these official sources:
- GitHub Blog: https://github.blog/latest/
- GitHub Changelog: https://github.blog/changelog/
- Awesome Copilot workflows: https://awesome-copilot.github.com/workflows/

Use `web-fetch` to read external public guidance from GitHub Blog, GitHub.com, and Awesome Copilot workflows. In particular, web fetch https://awesome-copilot.github.com/workflows/. Use GitHub repository API tools to read repository guidance or reference files instead of terminal, CLI, or sandboxed commands.

Update `site/content/github-info.md` with short, practical, developer-focused updates based on the latest GitHub Blog, GitHub Changelog, and Awesome Copilot workflow content. Mention the source whenever a change comes from the GitHub Blog, GitHub Changelog, or Awesome Copilot workflows, and keep the tone aligned with Mona's editorial notes.

Before finalizing the workflow configuration, check that the YAML frontmatter and tool settings are syntactically valid. Do not compile the workflow.

When the draft is ready, open a pull request for Mona to review. Use `safe-outputs` with `create-pull-request` so the agent can propose changes without writing directly to `main`. Title the pull request clearly and keep it in review mode for Mona's approval.
