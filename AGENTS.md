# AGENTS.md — OMI fixture (disposable)

Fixture repo for OMI gate runs. Plain Node.js (>= 22), ES modules, no dependencies.

- Source in `src/`, tests in `tests/*.test.js` using `node:test` + `node:assert/strict`.
- `npm test` must pass before a change is reviewed.
- Files listed as PO-owned in an Issue must not be created or modified by agents.
