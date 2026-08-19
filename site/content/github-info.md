# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Latest from the GitHub Blog

*Source: [GitHub Blog](https://github.blog/latest/)*

- **[How canvases make agentic workflows visible, steerable, and cost-efficient](https://github.blog/ai-and-ml/github-copilot/how-canvases-make-agentic-workflows-visible-steerable-and-cost-efficient/)** — Copilot canvases give developers a live view into what an agent is doing, letting you steer or stop it mid-task and avoid runaway costs. Practical for any team running multi-step agentic jobs. *(Aug 17, 2026)*

- **[How to bring your software delivery workflow into GitHub with agent apps](https://github.blog/ai-and-ml/github-copilot/how-to-bring-your-software-delivery-workflow-into-github-with-agent-apps/)** — Agent apps on GitHub Marketplace let you connect external tools directly into Copilot workflows without leaving GitHub. *(Aug 14, 2026)*

- **[Your contributors are AI-first now. Is your project?](https://github.blog/open-source/maintainers/your-contributors-are-ai-first-now-is-your-project/)** — Adding an `AGENTS.md` file to your repo helps AI agents understand how to contribute correctly — a quick win for open-source maintainers. *(Aug 12, 2026)*

- **[From coder to orchestrator: How agents shift the role of a developer](https://github.blog/developer-skills/career-growth/from-coder-to-orchestrator-how-agents-shift-the-role-of-a-developer/)** — Developers are increasingly directing agents rather than writing every line. A useful read for anyone thinking about how their workflow is changing. *(Aug 11, 2026)*

- **[A guide to slash commands in the GitHub Copilot app](https://github.blog/ai-and-ml/github-copilot/a-guide-to-slash-commands-in-the-github-copilot-app/)** — Quick reference for slash commands that speed up common Copilot tasks inside the app. *(Aug 6, 2026)*

## Latest from the GitHub Changelog

*Source: [GitHub Changelog](https://github.blog/changelog/)*

- **[Agent Plugins 1.0 in VS Code, Copilot CLI, and the Copilot app](https://github.blog/changelog/2026-08-12-agent-plugins-1-0-in-vs-code-copilot-cli-and-the-copilot-app)** — Agent plugins hit 1.0 across all three surfaces. Install community plugins with `copilot plugin install <name>@awesome-copilot`. *(Aug 12, 2026)*

- **[Grok 4.6 is now available in GitHub Copilot](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot)** — Another model option in Copilot's model picker for those experimenting with different LLMs on the same codebase. *(Aug 14, 2026)*

- **[Gemini 3.7 Flash is now available in GitHub Copilot](https://github.blog/changelog/2026-08-13-gemini-3-7-flash-is-now-available-in-github-copilot)** — Gemini 3.7 Flash joins the roster — useful for faster, lower-latency responses on routine tasks. *(Aug 13, 2026)*

- **[Enterprise managed settings in GitHub Copilot for JetBrains](https://github.blog/changelog/2026-08-18-enterprise-managed-settings-in-github-copilot-for-jetbrains)** — Admins can now push Copilot settings to JetBrains IDEs across the org without asking every developer to configure manually. *(Aug 18, 2026)*

- **[Rule insights for organizations in public preview](https://github.blog/changelog/2026-08-12-rule-insights-for-organizations-in-public-preview)** — See which branch protection rules are actually being triggered across your org — helpful for audits and cleaning up stale rules. *(Aug 12, 2026)*

## Awesome Copilot workflows

*Source: [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/workflows)*

The community `awesome-copilot` repo includes ready-to-use agentic workflow templates. Highlights:

- **`daily-issues-report`** — Schedules a daily GitHub issue summarizing new, closed, and stale issues. Good starting point for async team standups.
- **`weekly-comment-sync`** — Collects and syncs comments on a weekly cadence, useful for keeping distributed teams aligned.
- **`ospo-org-health`** and **`ospo-stale-repos`** — OSPO-focused workflows for monitoring org-wide repo health and flagging abandoned projects.
- **`relevance-check`** / **`relevance-summary`** — Automate triage by checking and summarizing issue relevance.

Install any workflow plugin with:

```bash
copilot plugin install <workflow-name>@awesome-copilot
```

Full collection at [awesome-copilot.github.com](https://awesome-copilot.github.com).
