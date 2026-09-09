# streakly

Small Vue 3 side project: track daily habits as a heatmap grid

Small but I use it weekly.

## Highlights

- Vite dev setup with hot reload
- State persisted to localStorage
- GitHub-style contribution grid per habit
- Composition API + script setup

## Getting started

```bash
npm install
npm run dev
```

## Usage

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Why

Needed this for myself; figured others might too.
