# unarchived journal

A local-first prompt drafting & writing tool. Single HTML file. No cloud, no tracking, no dependencies.

## What it is

Download `unarchived-journal.html`, open it in your browser, and start writing. Everything saves to your browser's localStorage—nothing leaves your computer.

Perfect for:
- Drafting detailed prompts for AI systems with structured templates
- Iterating on system instructions and context
- Keeping your prompt evolution private and offline
- Writing with focus—no distractions, no accounts

## Features

**Writing** — Contenteditable editor with monospace terminal aesthetic. Auto-saves as you type.

**Templates** — Pre-structured sections for prompt work:
- System (role & principles)
- Context (background)
- Instructions (steps & output format)
- Example (input/output pairs)
- Query (your question)
- Reference (links & files)

Plus markdown helpers: headings and links.

**Highlighting** — Select text and choose from 6 colors in 3 modes (text, background, both). Highlights persist and export correctly.

**Timer** — Optional focus sessions. Leave blank for stopwatch, enter minutes for countdown. Session duration records in exports.

**Export** — Download each entry as:
- Markdown (with YAML metadata, highlights preserved)
- HTML (standalone, fully styled)
- PDF (via browser print dialog)

**Storage** — All in localStorage. A 1,000-word prompt with highlights is ~6KB. You can maintain hundreds of prompts before hitting typical browser limits (5-10MB).

## Usage

1. Download the file
2. Open in any modern browser
3. Start writing

No server. No installation. No configuration. Works offline. Works forever.

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| Cmd/Ctrl + N | New entry |
| Cmd/Ctrl + S | Manual save |

## Philosophy

Part of **Unarchived** — tools for digital self-sovereignty. Your data, your computer, your control.

## License

MIT — Use, modify, fork, and share freely.
