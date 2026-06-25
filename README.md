# Nishant Chaudhary

**Senior Frontend Engineer** — React · TypeScript · AI tooling · New Delhi → open to EU remote

Building production component systems, MCP servers, and AI-powered developer tools.

---

## Flagship projects

### [mcp-react-toolkit](https://github.com/Nishant-Chaudhary5338/mcp-toolkit)
**17 MCP servers** for React + TypeScript development automation — wired to Claude Desktop, Cline, and Cursor, or run as plain CLI scripts.

[![CI](https://github.com/Nishant-Chaudhary5338/mcp-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/Nishant-Chaudhary5338/mcp-toolkit/actions/workflows/ci.yml)
[![npm](https://img.shields.io/npm/v/mcp-react-toolkit?label=npm)](https://www.npmjs.com/package/mcp-react-toolkit)
[![MCP Registry](https://img.shields.io/badge/MCP%20Registry-listed-blue)](https://registry.modelcontextprotocol.io)
[![Tests](https://img.shields.io/badge/tests-450%20passing-brightgreen)](https://github.com/Nishant-Chaudhary5338/mcp-toolkit)

```bash
npx mcp-react-toolkit --list          # all 17 servers
npx mcp-react-toolkit legacy-analyzer  # run one as an MCP server (stdio)
```

A selection (17 in total):

| Server | What it does |
|---|---|
| `component-factory` | Scaffold React components from 41 shadcn/ui templates — with tests + Storybook |
| `legacy-analyzer` | 22-tool health audit for any React/Next.js/Remix app — scores 0–100 + migration hints |
| `render-analyzer` | Detect unnecessary re-renders, missing memo, inline objects/functions |
| `performance-audit` | Memory leaks, heavy imports, unoptimized images, deep nesting |
| `typescript-enforcer` | Scan for `any` types, unsafe casts — 7 rules, scored 0–10 |
| `accessibility-checker` | WCAG 2.1 audit — alt text, ARIA roles, keyboard navigation |
| `generate-tests` | Analyze a TypeScript file and generate a Vitest test suite |
| `dep-auditor` | Unused deps, duplicates, circular imports, bundle impact |
| `monorepo-manager` | Workspace listing, dependency graph, health checks |
| `code-modernizer` | AST-based JS → TypeScript conversion |

### [code-graph-indexer](https://github.com/Nishant-Chaudhary5338/mcp-code-indexer)
Index any **TypeScript / React / Next.js** repo into a queryable **code graph** (files · components · functions, and the `imports`/`renders`/`calls`/`references`/`depends-on` edges between them) — then ask it precise questions instead of dumping files into an LLM's context. Built on `ts-morph`, so edges are **resolved, not grepped**.

[![npm](https://img.shields.io/npm/v/code-graph-indexer?label=npm)](https://www.npmjs.com/package/code-graph-indexer)

```bash
npx code-graph-indexer index --root .   # build the graph → .code-graph/graph.json
npx code-graph-indexer mcp              # serve 13 tools to Claude / Cursor
```

Four surfaces over one graph: a **CLI**, an **MCP server** (13 tools — `who_renders`, `who_calls`, `blast_radius`, `find_cycles`, `find_orphans`, `semantic_search`, …), an **HTTP/WS** server, and a **3D web explorer** (React + Three.js). Local **semantic search** (transformers.js, no API key) finds code by meaning. Token-safe by design — a `blast_radius` query is a few hundred tokens instead of streaming whole files.

---

## Other projects

| Project | Description | Stack |
|---|---|---|
| [dashcraft](https://github.com/Nishant-Chaudhary5338/dashcraft) | Headless dashboard library — cards, widgets, HTTP client, store | React · TypeScript |
| [react-present](https://github.com/Nishant-Chaudhary5338/react-present) | Presentation library — state, animation, gestures, themes | React · Framer Motion |
| [ai-builder](https://github.com/Nishant-Chaudhary5338/ai-builder) | Prompt → UI builder with Monaco Editor | React · OpenAI SDK |

---

## Stack

**Frontend** — React 19 · TypeScript strict · Next.js 15 · Tailwind CSS · Vite · Three.js · GSAP · Framer Motion

**AI / MCP** — Model Context Protocol · Claude SDK · ts-morph · transformers.js · Vitest

**Backend** — Node.js · Express · SQLite · Playwright · Turborepo · pnpm

---

## Find me

[![Portfolio](https://img.shields.io/badge/Portfolio-nishant.digitribe.world-black?style=flat)](https://nishant.digitribe.world/)
[![npm](https://img.shields.io/badge/npm-nishant--chaudhary-red?style=flat)](https://www.npmjs.com/~nishant-chaudhary)
[![Email](https://img.shields.io/badge/Email-nishantchaudhary.dev%40gmail.com-blue?style=flat)](mailto:nishantchaudhary.dev@gmail.com)
