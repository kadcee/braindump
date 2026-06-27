# Brain Dump

A personal thought capture tool. Type or speak ideas, AI sorts them into categories automatically.

Live at: `yourusername.github.io/repositoryname`

---

## Features

- Text and voice input
- AI auto-categorizes every idea (Work, Personal, Ideas, Health, Learning, Goals, Finance, Misc)
- Drag-and-drop between categories
- Status tags: Revisit Soon, Explore Later, Archive
- Priority star flag
- Quick capture mode (Enter key to add)
- Keyword search
- Timestamps on every idea
- Cross-category idea linking
- Mind map view with draggable nodes
- Weekly digest with stats
- Export and import JSON for syncing across devices

---

## Sync between devices

1. On device A, click "Export JSON" in the sidebar
2. Save the file to Google Drive or any shared storage
3. On device B, click "Import JSON" and select the file
4. Ideas merge without duplicates

---

## Tech

- Single HTML file, no build step, no backend
- React 18 via CDN
- Claude Sonnet 4.6 API for AI categorization
- Tabler Icons
- localStorage for persistence

---

## Run locally

Download `index.html` and open it in Chrome. No server needed.

---

## Deploy

Hosted on GitHub Pages. Any push to `main` updates the live site within ~60 seconds.
