# AGENTS.md

Operating notes for AI coding agents (Claude Code, Codex, Cursor, Copilot and others) working in this repository. Everything here is derived from the files actually in the tree, so trust it over guesses, and update it when the facts change.

## What this repository is

Runnable code examples for building on Robinhood Chain - SDK snippets, live price tickers, firehose consumers, agent scripts.

- Homepage: https://nirholas.github.io/robinhood-chain-examples/
- Source: https://github.com/nirholas/robinhood-chain-examples
- Primary language: JavaScript
- License: Other (see the LICENSE file)

## Repository layout

- `docs/`
- `examples/`
- `tools/`
- `README.md`
- `LICENSE`
- `package.json`

## Setup

```bash
npm install
```

## Commands

No build, test or lint scripts are declared in the tree. Verify changes by running the project as `README.md` describes.

## Conventions

- `.env` files are gitignored; never commit credentials, and read configuration from environment variables.
- Commit messages follow Conventional Commits (`type(scope): summary`), matching the existing history.
- Read the surrounding code before adding to it, and match its naming, file organisation and error-handling style.
- Keep `README.md` accurate: if a change alters behaviour, commands or configuration, update the docs in the same commit.
- Do not leave TODO comments, stub functions, placeholder data or commented-out code behind. Finish what you start or leave it out.
- Small, focused commits with a subject line that describes the change, not the act of committing.

## Where to raise things

- Bugs and feature requests: https://github.com/nirholas/robinhood-chain-examples/issues
- Questions and ideas: https://github.com/nirholas/robinhood-chain-examples/discussions
- Security issues: report privately at https://github.com/nirholas/robinhood-chain-examples/security/advisories/new, never in a public issue.
