# cody-public-snapshot

Public snapshot of Sourcegraph Cody (`sourcegraph/cody`) just before it went private — AI coding agent with deep codebase understanding.

> Full source lives in `cody-public-snapshot-main/`. See its `README.md` for upstream docs.

## What it is
- AI coding agent using LLMs + codebase context
- IDE clients: VS Code (`vscode/`), JetBrains, Neovim, CLI (`cli/`), Web (`web/`)
- Agent JSON-RPC server (`agent/`) for non-ECMAScript clients

## Getting Started
See upstream requirements (Node + pnpm historically). Example:
```bash
cd cody-public-snapshot-main
pnpm install
pnpm build
```

## Tech
- TypeScript, Node.js, VS Code extension API, JSON-RPC

## License
Apache-2.0 up to commit `d7fc6741e7893e3f6e29efe58043f1afe08d505f` — see `LICENSE` in snapshot.
