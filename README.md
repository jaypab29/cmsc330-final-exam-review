# CMSC330 Final Exam Study Guide

An interactive, single-file HTML study guide for **CMSC330: Organization of Programming Languages** at the University of Maryland. Built to help students review all major exam topics through live code editors, step-by-step animated diagrams, a cheat sheet, and a practice quiz — all without any dependencies or build steps.

Find the static webpage here: https://cmsc330-final-exam-review.onrender.com/

---

## 📖 Topics Covered

The content is based directly on previous CMSC330 final exams (Fall 2023, Spring 2024, Spring 2025) and course notes. Each section includes explanations, interactive elements, and exam-specific tips.

| # | Topic | Interactive Features |
|---|-------|----------------------|
| 1 | Regular Expressions | Live regex tester with match explanations |
| 2 | Finite State Machines | NFA → DFA subset construction stepper |
| 3 | Context-Free Grammars | Parse tree builder (step-by-step) |
| 4 | OCaml Fundamentals | Live OCaml simulator, type inference explorer |
| 5 | Higher-Order Functions | map / fold / filter playground |
| 6 | Lambda Calculus | β-reduction stepper, free/bound variable practice |
| 7 | Operational Semantics | Proof tree builder |
| 8 | Type Systems | Type judgment rules, exam problems from past finals |
| 9 | Rust & Ownership | Borrow checker simulator, ownership/move/borrow stepper |
| 10 | Garbage Collection | Reference counting + Mark-and-Sweep steppers |
| 11 | Interpreters & Compilers | Lexer / Parser / Evaluator stage failure table |
| 12 | Property-Based Testing | Live PBT runner with 100 random test cases |

---

## ✨ Features

- **Live Code Editors** — Edit and run code directly in the browser for OCaml (simulated), Rust borrow checking, regex testing, higher-order functions, and property-based testing. Every editor has a reset button to restore the original example.
- **Step-by-Step Diagrams** — All major algorithms (NFA→DFA, mark-and-sweep, ownership model, β-reduction, proof trees, parse trees, reference counting) are animated with Prev/Next navigation so you can walk through each step at your own pace.
- **Cheat Sheet** — A condensed reference covering OCaml syntax, regex operators, lambda calculus rules, Rust ownership, garbage collection, FSM algorithms, and a key True/False fact list drawn from past exams.
- **Practice Quiz** — 10 questions modeled after real CMSC330 final exam questions, with instant feedback and full explanations for every answer.
- **Sidebar Navigation** — Jump to any topic instantly, with a search bar to filter topics.
- **Zero Dependencies** — Pure HTML, CSS, and JavaScript. No frameworks, no npm, no build step. Open the file directly in any browser.

---

## 🚀 Usage

No installation required. Just open the file:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open cmsc330_study_guide.html   # macOS
# or
start cmsc330_study_guide.html  # Windows
# or double-click the file in your file explorer
```

Or view it directly on the Render link listed at the top of this page.

---

## 📁 Repository Structure

```
.
├── cmsc330_study_guide.html   # The complete study guide (single file)
└── README.md
```

---

## 🎯 Exam Tips Highlighted in the Guide

- **OCaml type inference ≠ dynamic typing** — OCaml is statically typed; the compiler infers types at compile time.
- **NFA → DFA:** Always show your ε-closure calculations. Add a dead/trap state for undefined transitions.
- **Lambda calculus:** Watch free vs. bound variables carefully when doing β-reduction across multiple steps.
- **Rust:** `String` is a move type; `i32` is a copy type. You cannot have a `&mut` borrow and any other borrow active simultaneously.
- **Garbage Collection:** Reference counting cannot handle cycles. Mark-and-sweep can.
- **`[OB]{2}`** matches exactly 2 characters from {O, B} — not 4. A common exam trap.

---

## 🛠️ Built With

- Vanilla HTML, CSS, and JavaScript — no external libraries
- [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans), [Space Mono](https://fonts.google.com/specimen/Space+Mono), and [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) via Google Fonts
- SVG for all interactive diagrams

---

## 📚 Based On

- CMSC330 course notes (University of Maryland)
- CMSC330 Final Exams: Fall 2023, Spring 2024, Spring 2025

---

## Disclaimer

- This webpage was generated based off of CMSC330 course notes using Claude Sonnet 4.6
- This webpage should not be treated as a comprehensive study guide, but rather as a tool to assist you
- This webpage may contain mistakes, review all information with caution

*Good luck on your final exam! 🎓*
