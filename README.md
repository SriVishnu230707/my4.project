# Mini Kanban UI

A compact, responsive Kanban-board demonstration made with plain HTML, CSS and JavaScript. It provides a simple visual workflow without requiring a framework or build process.

## Features

- Three workflow stages: To do, In progress and Done
- Add tasks from the page header
- Move a task by clicking it
- Responsive single-column layout on small screens
- No external dependencies

## Run locally

Open `index.html` in a modern browser, or start a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
.
├── index.html   # UI, styles and board interaction
└── README.md    # Documentation
```

This is a front-end UI model. Tasks are kept in memory and reset when the page reloads.
