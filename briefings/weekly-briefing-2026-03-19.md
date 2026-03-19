# Weekly AI Learning Briefing — March 19, 2026

---

## What I built & learned last week

- **Terminal & CLI basics** — `pwd`, `cd`, `mkdir`, `New-Item`; installed Chocolatey as a package manager
- **Git & GitHub setup** — `git init`, `git config`, `git add`, `git commit`, `git log`, `git push`; created `NikolaHDev` account and pushed first commits
- **JavaScript fundamentals** — `let` vs `const`, browser console as scratchpad, wrote first functions with arguments, conditions, and `console.log` output
- **Built two JS functions** — `weekSummary()` (weekly running mileage tracker) and `paceCalculator()` (min/mile pace calculator) — both domain-relevant to running/fitness interest
- **Portfolio site (`index.html`)** — built a full single-page portfolio with dark/light mode toggle, skills grid, contact form with submit handling, and live GitHub stats section using `fetch()` to the GitHub API with error handling
- **Week 1 quiz** — scored 9.5/10

---

## Where I left off

- Last commit (March 18): added the **live GitHub stats section** to `index.html` — fetches from `https://api.github.com/users/NikolaHDev` and displays repos, followers, following, member since; includes graceful error fallback
- The contact form (`handleSubmit`) currently only simulates a send — no backend/API hooked up yet
- No new commits since March 18; no Python, notebooks, or AI model code yet

---

## Worth reviewing before this week's sessions

- `fetch()` and async/await — the GitHub stats section uses it, good moment to understand the full pattern
- DOM manipulation basics — `getElementById`, `innerHTML`, `classList.toggle` all appeared in the portfolio
- The difference between `git commit` (local) and `git push` (remote) — noted as a confusion point in `notes.txt`

---

## This week's focus

- **Connect the contact form to a real backend** — good forcing function to learn about HTTP methods, form data, and a service like Formspree or a simple Node/Express endpoint
- **Start introducing Python or a basic AI/ML concept** — Week 1 was JS + HTML; the repo description is "ai-learning" but no AI tooling yet; a Jupyter notebook or simple OpenAI API call would be a natural next step

---
