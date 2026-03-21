# learning-qa-automation

A public learning repository for QA automation — theory, exercises, and solutions.
Built for manual testers who want to transition into automation engineering.

---

## What is this?

This repository is a structured collection of lecture notes and hands-on practice files covering test automation from the ground up. No production code — only learning materials.

Each topic follows the same pattern:

- **`N. TopicName.md`** — lecture: concepts explained with analogies, real-world examples, code samples with detailed comments
- **`N.0 TopicName Practice.md`** — exercises: basic → intermediate → advanced → expert levels, with solutions at the end

---

## Who is this for?

Manual QA engineers and testers who want to learn automation. The material assumes no prior programming experience. Concepts are introduced step by step, with a focus on "why do we need this" before "how does it work".

---

## Repository Structure

```
learning-qa-automation/
│
├── TS-Playwright/
│   ├── Part_1 - TypeScript Programming/    ← Done (11 topics)
│   │   ├── README.md                             ← Progress tracker
│   │   ├── 1. Variables.md
│   │   ├── 1.0 Variables Practice.md
│   │   ├── 2. Data Types.md
│   │   ├── 2.0 Data Types Practice.md
│   │   ├── 3. Loops.md
│   │   ├── 3.0 Loops Practice.md
│   │   ├── 4. Arrays.md
│   │   ├── 4.0 Arrays Practice.md
│   │   ├── 5. Strings and Methods.md
│   │   ├── 5.0 Strings Practice.md
│   │   ├── 6. Functions.md
│   │   ├── 6.0 Functions Practice.md
│   │   ├── 7. Async Await.md
│   │   ├── 7.0 Async Await Practice.md
│   │   ├── 8. Modules Import Export.md
│   │   ├── 8.0 Modules Import Export Practice.md
│   │   ├── 9. Interfaces.md
│   │   ├── 9.0 Interfaces Practice.md
│   │   ├── 10. Objects.md
│   │   ├── 10.0 Objects Practice.md
│   │   ├── 11. Classes OOP.md
│   │   └── 11.0 Classes OOP Practice.md
│   │
│   └── Part_2 - Playwright E2E/             ← Coming soon
│
└── README.md
```

---

## Part 1 — TypeScript Programming

Covers all TypeScript fundamentals needed to write Playwright tests professionally.

| # | Topic | What you'll learn |
|---|-------|-------------------|
| 1 | Variables | `var` / `let` / `const`, scope, hoisting |
| 2 | Data Types | `string`, `number`, `boolean`, `any`, union types, type annotations |
| 3 | Loops | `for`, `while`, `for...of`, `for...in`, `break` / `continue` |
| 4 | Arrays | Array methods, `map`, `filter`, `reduce`, tuples |
| 5 | Strings | String methods, template literals |
| 6 | Functions | Named, arrow, anonymous, callbacks, hoisting, scope, array methods |
| 7 | Async / Await | Promises, `async/await`, `try/catch`, `Promise.all` |
| 8 | Modules | Named/default export, import syntax, project structure |
| 9 | Interfaces | Optional fields, readonly, extends, implements, Page Object Model |
| 10 | Objects | Object declaration, nested objects, methods |
| 11 | Classes & OOP | Constructors, inheritance, `abstract`, Page Object Model |

---

## Part 2 — Playwright E2E (coming soon)

- Installation and first test
- Locators and selectors
- Actions: click, fill, navigate
- Assertions with `expect`
- Page Object Model — applying OOP from Part 1
- Fixtures and test hooks
- Screenshots and video
- Parallel test execution

---

## How to use

Clone the repository and open the files in any Markdown editor. The files work best in [Obsidian](https://obsidian.md) — links between notes are formatted for Obsidian's internal linking system.

```bash
git clone https://github.com/your-username/learning-qa-automation.git
```

Open the `README.md` inside each Part folder to track your progress through the topics.

---

## Contributing

This is a personal learning project. Pull requests are reviewed manually — feel free to open an issue if you find an error or have a suggestion.

---

*Author: Denys — manual QA tester learning automation, based in Spain.*
