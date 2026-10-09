# 🧭 Skill Suggester (Always-On Agent Advisor)

> **Proactively connects every prompt to the best agent skill in Antigravity, Claude Code, and open-agent harnesses.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Antigravity Ready](https://img.shields.io/badge/Antigravity-Skill-purple.svg)](https://github.com)
[![Always-On Mode](https://img.shields.io/badge/Mode-Always--On-success.svg)](#how-it-works)

Stop "vibe coding" with generic LLM responses. **Skill Suggester** operates in the background, matching user problems against curated agent skills (TDD, Ponytail, Diagnosing-bugs, Blueprint, Code-review, Architecture improvements, and more) to guarantee disciplined software engineering.

---

## 🚀 Key Features

* **⚡ Always-On Proactivity:** Silently listens and detects when a specialized workflow provides a superior outcome.
* **🎯 High-Signal Recommendations:** Injects concise 1–2 line guidance blocks without cluttering your conversation.
* **🔄 Seamless Adoption:** Can either suggest the skill for user approval or immediately adopt the matched methodology.
* **📚 Integrated Catalog:** Covers 300+ skills across testing, debugging, architecture, minimalism, cloud, and agent harnesses.
* **🌐 Universal Compatibility:** Works seamlessly with Google Antigravity, Claude Code, Cursor, and any markdown-based skill runner.

---

## 🧩 How It Works

Whenever you ask a question or propose a task, **Skill Suggester** maps the intent:

```
User Prompt (e.g., "This endpoint is returning 500 intermittently")
   │
   ▼
Intent Detection & Catalog Match
   │
   ├─► Matches: diagnosing-bugs (non-deterministic bug loop)
   │
   ▼
Proactive Suggestion Badge
   💡 Recommended Skill: `diagnosing-bugs`
   Reason: Construct a 100x reproduction harness before touching business logic.
   │
   ▼
Execution with Specialized Methodology
```

---

## 📋 The Routing Matrix

| When You're Doing... | Skill Suggester Recommends... | Primary Impact |
| :--- | :--- | :--- |
| **Fixing a bug / regression** | `diagnosing-bugs` | 6-phase loop from repro harness to cleanup. |
| **Building a feature test-first** | `tdd` / `tdd-workflow` | Red-Green-Refactor, vertical slices, 80%+ coverage. |
| **Designing multi-PR project** | `blueprint` | Step-by-step construction plan with cold-start briefs. |
| **Pruning bloat & over-engineering** | `ponytail` | Lazy senior developer ladder (YAGNI $\rightarrow$ Stdlib $\rightarrow$ Native). |
| **Reviewing diffs or PRs** | `code-review` | Two-axis review: documented Standards vs. originating Spec. |
| **Refactoring module depth** | `improve-codebase-architecture` | Visual HTML/Mermaid before/after architectural review. |
| **Evaluating ideas or PRDs** | `grill-me` | Depth-first interactive interview questioning every decision. |
| **Building AI agents or harnesses** | `agents-best-practices` | Provider-neutral loop, tool permission, and eval blueprints. |

---

## 📦 Installation

### Option 1: In Google Antigravity (Local)

1. **Global Skills Folder:**
   Copy the `skill-suggester` folder into your global skills directory:
   ```bash
   cp -r skill-suggester ~/.gemini/config/skills/skill-suggester
   ```

2. **Plugin Folder:**
   Or add it as a plugin:
   ```bash
   cp -r skill-suggester ~/.gemini/config/plugins/skill-suggester-plugin/skills/skill-suggester
   ```

### Option 2: In Claude Code (`~/.claude/skills`)

```bash
mkdir -p ~/.claude/skills/skill-suggester
cp SKILL.md ~/.claude/skills/skill-suggester/
```

---

## 📤 How to Upload This Repository to GitHub

To publish this skill repository to your GitHub account:

1. **Initialize git and commit the files:**
   ```bash
   git init
   git add .
   git commit -m "feat: initial commit of skill-suggester"
   ```

2. **Create the repository on GitHub:**
   * Using GitHub CLI (`gh`):
     ```bash
     gh repo create skill-suggester --public --source=. --remote=origin --push
     ```
   * Or manually on GitHub:
     1. Go to [github.com/new](https://github.com/new).
     2. Create a repository named `skill-suggester`.
     3. Link and push your local repository:
        ```bash
        git remote add origin https://github.com/<YOUR-USERNAME>/skill-suggester.git
        git branch -M main
        git push -u origin main
        ```

---

## 📄 License

Released under the [MIT License](LICENSE).
