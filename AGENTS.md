# Repo Instructions for Codex / Claude Code

You are working inside my project repository.

Important context:
This project is part of my personal AI operating system and internal real estate tool development workflow. The goal is to build practical tools that help with property search, sales operations, Google Sheets data, automation, AI workflows, dashboards, and internal productivity.

General rules:

* Always inspect the existing code before making changes.
* Preserve current functionality unless the task explicitly says to remove it.
* Prefer small, incremental changes.
* Do not over-engineer.
* Do not introduce unnecessary dependencies.
* Do not hardcode secrets, API keys, tokens, passwords, or private URLs.
* If environment variables are needed, document the variable names clearly.
* If changing data mapping, explain which fields/columns are affected.
* If modifying UI, keep it mobile-first, clean, fast, and easy for salespeople to use.
* If modifying Google Sheets integration, be careful with column mapping and missing values.
* If adding automation, include logging and error handling.
* If adding AI behavior, include guardrails and human approval for sensitive actions.

Preferred workflow:

1. Read the task.
2. Inspect relevant files.
3. Summarize what you found.
4. Propose a short plan.
5. Make the smallest safe change.
6. Explain what changed.
7. Provide test steps.
8. Mention any risks or follow-up improvements.

Project priorities:

* Reliability first.
* Fast mobile UX.
* Simple data flow.
* Easy maintenance.
* Clear business value.
* Low-cost implementation.
* Human approval for risky actions.

When uncertain:

* Make a reasonable assumption.
* State the assumption clearly.
* Continue with the safest implementation.
