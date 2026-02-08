# CLAUDE.md

Surfaces macOS Screen Time data (app usage, limits) as MCP tools. Reads data via AppleScript.

## Stack

TypeScript, Node.js >=18, ESM, MCP SDK

## Build & Test

```sh
npm run build        # tsc
npm test             # vitest run
npm run lint         # eslint src
npm run format:check # prettier --check .
npm run dev          # tsc --watch
```

## Conventions

- Entry point is `src/index.ts`; unit tests are in `src/__tests__/`
- ESLint 9 flat config, Prettier formatting, Husky + lint-staged for pre-commit checks
- Requires macOS Screen Time to be enabled in System Settings
