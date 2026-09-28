# streakly

Small Vue 3 side project: track daily habits as a heatmap grid

## Examples

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Install

```bash
npm install
npm run dev
```

## Highlights

- Composition API + script setup
- Vite dev setup with hot reload
- GitHub-style contribution grid per habit
- State persisted to localStorage

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
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
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
