# AIGP Study Kit

**Free, unofficial practice exams and study tools for the IAPP AIGP (Artificial Intelligence Governance Professional) certification** — 341 original practice questions across five full-length mock exams, 54 framework recall cards, and a 3-week study plan, all cited against IAPP's AI Governance Professional Body of Knowledge v2.1.

**[→ Open the study kit](https://jasondmacleod.github.io/aigp-study-kit/)** (or open any file in `tools/` directly in a browser — no install, no account, no sign-up)

> **This is not an official IAPP product.** It is an independent study aid built by one candidate while preparing for the AIGP exam, shared publicly in case it's useful to other candidates. It is not affiliated with, endorsed by, or produced in partnership with IAPP or Wiley. AIGP®, IAPP®, CIPP®, CIPM® and CIPT® are trademarks of IAPP. See [DISCLAIMER.md](DISCLAIMER.md) for the full statement, sourcing notes, and trademark/copyright details.

---

## What's inside

| Tool | File | Contents |
|---|---|---|
| 3-Week Study Plan | [`tools/study-tool.html`](tools/study-tool.html) | Session-by-session plan mapped to BoK v2.1 domains, plus 20 diagnostic drill questions |
| Framework Recall Cards | [`tools/framework-recall.html`](tools/framework-recall.html) | 54 cards on the frameworks the exam expects cold: NIST AI RMF, ISO/IEC 42001/42005, the EU AI Act, and more |
| Mock Exam A | [`tools/mock-exam-a.html`](tools/mock-exam-a.html) | 71 questions, full-length, scenario-based |
| Mock Exam B | [`tools/mock-exam-b.html`](tools/mock-exam-b.html) | 68 questions, independent question set |
| Mock Exam C | [`tools/mock-exam-c.html`](tools/mock-exam-c.html) | 66 questions, reweighted toward under-drilled BoK indicators, includes multi-select |
| Mock Exam D | [`tools/mock-exam-d.html`](tools/mock-exam-d.html) | 68 questions, includes ordering and select-all-that-apply formats |
| Mock Exam E | [`tools/mock-exam-e.html`](tools/mock-exam-e.html) | 68 questions, intended as a final readiness check |

**341 practice questions in total.** Every mock exam is fully self-contained — a single HTML file with inline CSS and JavaScript, no build step, no dependencies beyond a Google Fonts stylesheet. Open it in any browser, on any device, offline-capable once loaded.

## How to use it

Open any file above directly in a browser, or visit the [GitHub Pages site](https://jasondmacleod.github.io/aigp-study-kit/) for a linked overview of all seven tools. Each mock exam offers two modes:

- **Timed** — a running clock, answers and explanations hidden until you submit, matching the real exam's pacing (~1.8 minutes/question, mirroring the official 180-minute exam).
- **Untimed practice** — answers and explanations reveal as you go, better suited to early-stage learning than to a readiness check.

Progress (answers, flags, timer state) is saved to your browser's `localStorage` only. Nothing is sent to a server, nothing is tracked, and nothing carries over between browsers or devices — that's a limitation to know about, not a bug: if you switch browsers partway through an exam, you'll restart it.

## Sourcing and citation approach

All questions, scenarios, answer options, and explanations are **original content**, written from scratch — none of it is copied or adapted from IAPP's official practice exam. Two citation types appear on every question:

1. **BoK performance indicator** — the specific IAPP AIGP Body of Knowledge v2.1 indicator the question targets, quoted in IAPP's own wording. The BoK is free to download from [iapp.org/certify/aigp](https://iapp.org/certify/aigp/); citing it lets you trace a wrong answer straight back to the source material instead of guessing at what to review.
2. **Study-guide reference** — a chapter and section name from the Wiley AIGP study guide, as a pointer only (no text from the book is reproduced).

IAPP's official practice exam was reviewed only for topic-coverage and question-format ratios (how heavily each domain is weighted, and roughly what share of questions are scenario-based vs. direct recall) — never for question text, options, or explanations.

## Known content landmines

A couple of places where the "textbook answer" and "currently true" answer diverge — worth knowing regardless of which one the exam wants on test day:

- **EU AI Act high-risk timelines.** Regulation (EU) 2026/1744 (the "Digital Omnibus on AI"), in force since 27 July 2026, deferred Annex III high-risk obligations to 2 December 2027 and Annex I to 2 August 2028. Prohibitions, GPAI rules, and the August 2027 GPAI grace period are unchanged. If a question's "textbook" answer predates this, that's the BoK's framing, not an error in this kit.
- **Colorado's AI Act.** Colorado's SB 205 (the Colorado AI Act) was repealed before its original effective date. Some legacy study material still treats it as current law — this kit does not.

## Known limitations

- **Scenario coverage.** These mock exams run roughly 16% scenario-based questions, versus IAPP's official practice exam at roughly 27%. Use these for domain-knowledge and recall practice; don't treat the scenario ratio as fully representative of exam day.
- **Not a substitute for the BoK.** Passing the AIGP exam requires studying IAPP's official Body of Knowledge. This kit is a supplement — recall reinforcement and self-assessment — not a replacement.
- **May contain errors.** This is one candidate's self-built study material, not professionally edited or IAPP-reviewed. If you spot a mistake, please open an issue.

## License

This repository draws on two different kinds of content, licensed differently:

- **Original content** (questions, scenarios, explanations, code, and this README) is © the repository author, licensed under **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)** — you may share and adapt it non-commercially, with attribution, under the same license. See [LICENSE](LICENSE).
- **Third-party citations** (BoK v2.1 performance-indicator text, study-guide chapter/section names) are **not licensed by this repository**. BoK text is © IAPP; the study guide is a copyrighted work published by Wiley. See [DISCLAIMER.md](DISCLAIMER.md) for details.

## Contributing

Found an error, an outdated date, or a broken link? Open an issue or a pull request — corrections are welcome.
