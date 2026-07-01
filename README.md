# Circle the Ball!

A simple browser game: a happy ball bounces around the screen, and you score points by moving your mouse in circles around it. Each full loop = 1 point.

## Play

Just open `index.html` in any browser, or play it online once GitHub Pages is enabled.

## How it works

- The ball bounces with physics (gravity + wall collisions).
- The game tracks the angle of your mouse around the ball and accumulates rotation.
- Every full 360° loop bursts particles and scores a point.
- Best score is saved in `localStorage`.

Works on desktop (mouse) and touch devices (finger drag).

---

# IT Project Tracker (`tracker.html`)

A phone-first web app for the movement's IT team to list and manage all projects
and apps across segments (Apps & Web, Data & Analytics, Infra & Security, Comms,
Internal Tools, …).

## Use it

Open `tracker.html` on your phone (or add it to your home screen for an app-like
feel). Everything is saved locally on the device via `localStorage` — no server,
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
