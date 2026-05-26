# 🐔 WizeChicken Control Dashboard

Single-file dashboard for the [wizechicken-analytics](https://github.com/officeUniverse/wizechicken-analytics) automation system.

**Live:** https://officeuniverse.github.io/wizechicken-dashboard/

## How it works

- Pure static HTML/JS — no backend, no server
- Stores your GitHub Personal Access Token in browser localStorage only
- Calls GitHub API directly from your browser
- Token never leaves your machine

## What it shows

- Channel analytics (28-day stats, retention, traffic sources)
- ICAHN topic picks with one-click "Generate this" buttons
- Videos awaiting your thumbnail review
- Recent workflow runs

## Setup

1. Open https://officeuniverse.github.io/wizechicken-dashboard/
2. Generate a GitHub PAT with `repo` + `workflow` scopes
3. Paste it once on the setup screen
4. Done
