# IT Project Tracker

A phone-first web app for a movement's IT team to list and manage all projects
and apps across segments (Apps & Web, Data & Analytics, Infra & Security, Comms,
Internal Tools, …).

## Open it

- Live: **https://tanjamik.github.io/ball-circle-game/**
- Or open `index.html` in any browser.

On your phone, add it to the home screen for an app-like feel
(iOS Safari: Share → *Add to Home Screen*; Android Chrome: ⋮ → *Add to Home screen*).

Everything is saved locally on the device via `localStorage` — no server,
no accounts.

## Features

- List all projects grouped by segment, with live counts.
- Per-project: segment, status (Idea / Active / On hold / Done), priority, owner,
  a link (repo / staging / doc) and notes.
- Add, edit and delete projects from a bottom sheet.
- Task checklist per project with a progress bar.
- Search across names, notes, owners and tasks; filter by segment.
- Header stats: total projects, active projects, open tasks.

It ships with a few example projects so you can see the layout — delete them and
add your own.
