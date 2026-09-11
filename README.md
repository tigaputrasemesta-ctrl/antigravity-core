# Antigravity Core (AGY) ⚡

[![Powered by Antigravity](https://img.shields.io/badge/Powered%20by-Antigravity%20AGY-blue.svg)](https://antigravity.google)
[![Cognitive Engine](https://img.shields.io/badge/Cognitive%20Engine-Claude%203.7%20Level-purple.svg)](#claude-cognitive-architecture)
[![TypeScript Strict](https://img.shields.io/badge/TypeScript-Strict%20Mode-blue.svg)](#elite-coding-standards)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Antigravity Core** is an enterprise-grade agent configuration template for Google Antigravity (AGY). It equips the AI agent with **Claude-caliber cognitive reasoning**, **elite fullstack web application architecture skills**, and **surgical, defensive coding standards**.

---

## 🧠 1. Claude Cognitive Architecture (Extended Thinking)

AGY operates under an extended first-principles reasoning loop:

1. **Problem Space Deconstruction**: Breaks down user requirements into fundamental logic, system invariants, and edge conditions before writing a single line of code.
2. **Multi-Hypothesis & Trade-off Evaluation**: Compares competing architectural designs (performance vs. simplicity, client compute vs. network I/O).
3. **Adversarial Self-Critique (Pre-Mortem)**: Tests every solution against failure modes, race conditions, memory leaks, and unhandled boundary cases.
4. **Epistemic Rigor & Zero Hallucination**: Verifies actual file paths, real API signatures, and package dependencies instead of guessing.

---

## 🛠️ 2. Included Workspace Skills (`.agents/skills/`)

Modular skills automatically discovered and progressively loaded by Antigravity:

| Skill | Path | Description |
| :--- | :--- | :--- |
| **`claude-thinker`** | [`.agents/skills/claude-thinker/`](./.agents/skills/claude-thinker/) | Deep analytical reasoning, root-cause analysis (5-Whys RCA), and Architectural Decision Records (ADR). |
| **`web-app-architect`** | [`.agents/skills/web-app-architect/`](./.agents/skills/web-app-architect/) | Fullstack mastery for React 19, Next.js App Router (RSC), Zustand, TanStack Query, Prisma/Drizzle ORM, and REST/tRPC APIs. |
| **`web-security-performance`** | [`.agents/skills/web-security-performance/`](./.agents/skills/web-security-performance/) | OWASP Top 10 security hardening, HttpOnly cookies, input sanitization, and Core Web Vitals optimization (LCP, INP, CLS). |
| **`code-craftsman`** | [`.agents/skills/code-craftsman/`](./.agents/skills/code-craftsman/) | Test-Driven Development (TDD), Vitest/Jest/Playwright test suites, defensive programming, and regression-free refactoring. |

---

## 📋 3. Enforced Rules (`.agents/rules/` & Root Directives)

- **[`AGENTS.md`](./AGENTS.md) / [`GEMINI.md`](./GEMINI.md)**: Universal root instructions governing AGY's identity, cognitive depth, and operational discipline.
- **[`claude-reasoning.md`](./.agents/rules/claude-reasoning.md)**: Extended thinking protocols and mental simulation checklist.
- **[`web-engineering.md`](./.agents/rules/web-engineering.md)**: Frontend/backend separation of concerns, hydration safety, and database querying rules.
- **[`coding-standards.md`](./.agents/rules/coding-standards.md)**: Strict typing, clean code invariants, and error-handling standards.

---

## 🚀 4. How to Use in Your Project

Clone or copy this structure into any repository root:

```bash
git clone https://github.com/tigaputrasemesta-ctrl/antigravity-core.git
cp -r antigravity-core/.agents your-project/
cp antigravity-core/AGENTS.md your-project/
cp antigravity-core/GEMINI.md your-project/
```

Once placed in the workspace root, Antigravity will automatically discover and enforce all cognitive rules and specialized skills.

---

## 📄 License

MIT © [CV Tiga Putra Semesta](https://github.com/tigaputrasemesta-ctrl)
