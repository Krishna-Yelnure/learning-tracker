# Learning Tracker

A single-file learning outcome tracker built with vanilla HTML/CSS/JS. No build step, no dependencies, no backend.

## Features

**Subjects & structure**
- 4 pre-loaded subjects — Mathematics, Computational Thinking, Statistics, Python
- Multi-subject switcher with per-subject colour theming
- Week sections with collapsible outcome lists and progress rings

**Per-outcome panel**
- 4-tab panel — Details, Mastery, Recall, Mistakes
- Mastery stars (Exposure → Mastery) + attempts counter
- Difficulty Score = Attempts × (5 − Stars)

**Week & outcome management**
- Week CRUD with ⋯ context menu — Edit, Add Outcome, Delete
- Drag-to-reorder outcomes in Edit Week modal
- Inline Add Outcome — Enter to add, Esc to dismiss

**Queues & search**
- Need Help / To Review queue system (desktop toolbar + mobile strip)
- Full-text outcome search

**Habit & focus tools**
- 🔥 Daily streak counter — consecutive days with any activity
- ⏳ Exam countdown per subject — urgency tiers (grey → amber → red)
- 🍅 Pomodoro timer — draggable floating widget, 25/5 with 4-session cycle, circular ring, sound alerts, session log, configurable durations

**Stats**
- Total Outcomes, Completed, XP Earned, Avg Confidence, Study Hours
- Study Hours unlocked by Pomodoro — tracked per subject in localStorage

**Data**
- Save/Load progress as JSON
- Installable as a PWA (Chrome, Edge, Android, iOS 16.4+)

## Usage

Open `index.html` directly in a browser — or visit the live version: `username.github.io/learning-tracker`

For PWA install (adds to home screen / desktop), open the live link in Chrome or Edge. Requires HTTPS — host via `npx serve .`, GitHub Pages, or Netlify Drop.

## Rating

Current build: **9.9 / 10**
