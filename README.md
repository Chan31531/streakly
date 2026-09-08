# streakly

Small Vue 3 side project: track daily habits as a heatmap grid

Side project, maintained when I have time.

## Usage

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Features

- State persisted to localStorage
- GitHub-style contribution grid per habit
- Composition API + script setup
- Vite dev setup with hot reload

## Installation

```bash
npm install
npm run dev
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
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

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.
