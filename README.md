# CPA Digital Finance Flashcards

A self-contained, browser-based study tool for the CPA Australia Digital Finance exam. 371 exam-focused flashcards with spaced repetition, quiz mode, and progress tracking — all in a single HTML file, no server required.

## What It Does

- **371 flashcards** covering all 5 modules, weighted to match the exam:
  - M1: Digital Finance Ecosystem (65 cards, 20%)
  - M2: Future of Money (55 cards, 15%)
  - M3: Technology in Finance (78 cards, 20%)
  - M4: Data Analytics (93 cards, 25% — highest weighted)
  - M5: Risk, Governance & Compliance (80 cards, 20%)

- **Two study modes:**
  - **Flip Card** — tap to reveal the answer, then self-rate (Again / Hard / Good / Easy)
  - **Quiz Mode** — 4-option multiple choice with instant feedback

- **SM-2 spaced repetition algorithm** — the same algorithm behind Anki. Cards you struggle with appear more often; cards you know well fade into longer intervals.

- **Smart filtering** — filter by module, search by keyword, or focus on due/new/difficult cards only.

- **Progress dashboard** — track mastery rate, accuracy, and per-module progress at a glance.

## How to Use

1. Open `index.html` in any browser — desktop or mobile
2. Pick a mode (Flip Card or Quiz)
3. Filter by module if you want to focus on specific areas
4. Rate honestly — the algorithm adapts to your actual knowledge gaps
5. Come back daily — spaced repetition works best with consistent short sessions

Your progress is saved in your browser's localStorage. No account needed.

## Tech

Single HTML file. No dependencies, no build step, no server.

- Vanilla JavaScript
- SM-2 spaced repetition algorithm
- CSS Grid layout, responsive down to mobile
- localStorage for progress persistence
- Content extracted from the CPA Australia Digital Finance Study Guide (1st Edition, Semester 2 2022)

## Source Material

All flashcard content is based on the CPA Australia Digital Finance Study Guide. This tool is intended as a personal study aid and does not reproduce the guide's content verbatim.

## Credits

Built by **Ana Ululiyatul** with AI assistance (Claude, Anthropic).

## License

MIT — use it, fork it, share it with your study group.
