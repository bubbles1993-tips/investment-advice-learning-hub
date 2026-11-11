# Investment Advice learning hub

Personal, independent study companions covering FPC008 Topics 1–3.

**Site:** https://bubbles1993-tips.github.io/investment-advice-learning-hub/

This repository and GitHub Pages site are separate from the travel journal. GitHub serves the pages even when the work laptop is off. An internet connection is required; a home-screen shortcut does not provide guaranteed offline access.

## Contents

- Topic 1: discovery, documentation and the client's financial position (1.1–1.3).
- Topic 2: constraints and behavioural influences (2.1–2.2).
- Topic 3: performance metrics and research quality (3.1–3.2).

The guides include worked examples, interactive study tools, recall cards, original practice questions and notes. They are not official Kaplan resources, assessment answers or personal financial advice. Full readings and assessment instructions remain in KapLearn.

## Hosting and study data

GitHub Pages publishes `docs/` from `main`. The pages use relative links and self-contained HTML, CSS and JavaScript. `.nojekyll` keeps publishing static.

Notes, completion ticks and quiz answers are stored in each browser's local storage. The site does not upload them and they do not automatically sync. Use the hub's progress export/import to move study data between devices or from local files to the hosted address. Back up before replacing data. Keep backups private.

Only the eight finished HTML files and `.nojekyll` belong in `docs/`. Original course PDFs, source extracts, local build files, screenshots and progress backups are excluded. The root `.gitignore` uses an explicit publication allowlist.

## Updating

Generate and validate the learning guides in the private local workspace, then copy the eight HTML outputs into `docs/`. Review the diff and commit only the intended publication files to `main`; GitHub Pages rebuilds from that branch. When adding a module, update the hub registry, navigation and publication allowlist together.
