# ⚡ SparkyBot Command Center

Kanban dashboard for SparkyBot — task management, GitHub sync, and anomaly tracking.

## Features

- **Drag & drop** kanban board (Backlog → To Do → In Progress → Review → Done)
- **Create, edit, delete** tasks with priority and project assignment
- **GitHub Issues sync** — create/update issues from the dashboard
- **Anomaly dashboard** — monitor system health and error tickets
- **Project filtering** — view tasks by project
- **Auto-refresh** every 30 seconds
- **Dark theme** command center aesthetic

## Setup

1. Visit the dashboard URL
2. Enter your Supabase URL and anon key (stored locally in browser)
3. Start managing tasks!

## Tech

Single HTML file — no build step required. Uses:
- React 18 (CDN)
- Tailwind CSS (CDN)
- Supabase JS Client (CDN)
- JetBrains Mono + DM Sans fonts

## Hosting

Hosted on GitHub Pages from the `main` branch.

## Security

- Supabase credentials stored in browser localStorage only
- Never committed to the repo
- Requires Supabase RLS policies for production use
