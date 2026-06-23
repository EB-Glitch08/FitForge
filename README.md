# FitForge

A home fitness tracking web app for logging workouts set-by-set, with structured pull-movement programming.

**[▶ Live Demo](https://eb-glitch08.github.io/FitForge/)**

## About

FitForge is a web app for tracking home workouts with precision and minimal friction. Instead of recording an exercise as a single entry, it captures every set — weight and reps — so progression is visible rep-by-rep over time. It includes structured programming for pull movements (often missing from home routines) to keep training balanced, and tracks personal records automatically.

Built as a single self-contained HTML file with vanilla JavaScript, and backed by an automated test suite to keep the logging logic reliable.

## Features

- **Per-set logging** — record weight and reps for each individual set, not just the exercise
- **Automatic PR tracking** — personal records are detected and stored per exercise, with a "🏆 Beat!" indicator when you exceed a previous session
- **Pull-movement programming** — progressive pulling exercises (rows, pull-up negatives, full pull-ups) that scale with your level
- **Progress charts** — visual tracking of your training over time, powered by Chart.js
- **Local-first** — all data stored in your browser; no account, no sign-up, fully private

## Tech Stack

- Vanilla JavaScript (no framework)
- HTML & CSS
- [Chart.js](https://www.chartjs.org/) for progress visualisation
- jsdom test suite (92 assertions across 25 sections)

## Running Locally

It's a single HTML file — no build step required:

```bash
# Clone the repo
git clone https://github.com/EB-Glitch08/FitForge.git

# Open it
cd FitForge
open index.html    # or just double-click the file
```

## Disclaimer

FitForge is a personal training tracker, not medical advice. Consult a doctor before starting any new exercise programme.

## License

MIT — see [LICENSE](LICENSE) for details.
