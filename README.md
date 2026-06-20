# AWS Prep Game

A single-file, browser-based AWS preparation quiz designed for practice and progress tracking.

## Overview

- File: [aws_game.html](aws_game.html)
- Contains a 60-question multiple-choice quiz across common AWS topics (Compute, Storage, Networking, Security, Databases, Architecture).
- Provides immediate feedback, brief explanations, and records progress locally in the browser.

## Features

- Choose a single topic or `All Topics (Mixed)`.
- Select number of questions (1–60) for each quiz.
- Immediate correct/incorrect feedback with an explanation and the correct answer shown when necessary.
- Per-quiz summary: correct/wrong counts, percentage, and time spent.
- Progress page saving recent quizzes locally (browser `localStorage`).
- Tracks daily time spent and number of days visited.
- Badge reward system (bronze/silver/gold) based on quiz scores.
- Help page and first-time instructions popup.
- Clear saved data option.

## How to use

1. Open [aws_game.html](aws_game.html) in your browser (double-click or drag into a browser window).
2. Select a topic (or `All Topics`) and set the number of questions.
3. Click **Start Quiz**. Choose an answer for each question — you will see immediate feedback and a short explanation.
4. At the end, review your results and suggestions for areas to improve.
5. Visit the **Progress** panel to view past quizzes, badges, and daily time.

## Data & Privacy

- All progress, badges, and daily time are stored locally in your browser's `localStorage` (no data is sent to a server).
- To reset stored data, use the **Clear Data** button in the Progress panel.

## Badge thresholds

- Gold: >= 90% on a quiz
- Silver: >= 75% and < 90%
- Bronze: >= 50% and < 75%

## Troubleshooting

- If the UI doesn't show or the quiz doesn't start, try a modern browser (Chrome, Edge, Firefox) and ensure JavaScript is enabled.
- If progress does not appear, check browser storage settings or try in a different browser/profile.

## Improving or customizing

- Questions and explanations are embedded in `aws_game.html` — edit that file to add or modify questions.
- You can change visual styles in the file's `<style>` block.

## Next steps (optional)

- Export/import progress data (not implemented) to back up or transfer progress.
- Add user accounts and server-side persistence (would require a backend).

---

Created for local practice and testing. If you want, I can add an export/import feature or convert this into a small web app with server-side storage.
