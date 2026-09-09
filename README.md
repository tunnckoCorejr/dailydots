# dailydots

Small Vue 3 side project: track daily habits as a heatmap grid

Small but I use it weekly.

## Install

```bash
npm install
npm run dev
```

## How to use

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## Highlights

- Composition API + script setup
- Vite dev setup with hot reload
- State persisted to localStorage
- GitHub-style contribution grid per habit

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
├── scripts/
│   └── dev.sh
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas

## License

MIT - see [LICENSE](LICENSE).
