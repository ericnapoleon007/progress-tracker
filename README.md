# Progress & Career Impact Tracker

This repository contains your comprehensive career progress log, project deep dives, and an interactive visual dashboard designed for supervisor 1-on-1s and performance reviews.

## Quick Start: View the Dashboard

To open your interactive visual dashboard:
- Simply double-click [`index.html`](file:///Users/ericnapoleon/Downloads/progress%20tracker/index.html) in Finder, or run:
```bash
open index.html
```

## Structure

```text
progress-tracker/
├── index.html            # Interactive visual dashboard (Timeline, Projects, Supervisor 1-on-1 Mode)
├── WORK_LOG.md           # Master executive markdown report (copy-pasteable for Slack/email/reviews)
├── data/
│   └── records.json      # Structured database of all activities, milestones, and projects
└── README.md             # This guide
```

## How to Add New Records

You have two easy ways:
1. **Tell me:** Just drop raw notes or bullets in chat, and I'll update both `data/records.json`, `index.html`, and `WORK_LOG.md` simultaneously.
2. **From the Dashboard UI:** Click the **"+ Add Entry"** button on the top right of the dashboard.
