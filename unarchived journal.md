# unarchived journal

A local-first journal that looks like your terminal. Highlights, timer, PDF/MD/HTML export. One HTML file. No cloud. No dependencies.

## What it is

A single HTML file you open in your browser. You write in it. It saves to localStorage. Nothing leaves your machine.

The editor uses a monospace terminal aesthetic with a prompt symbol, but the writing experience is fluid and distraction-free. Select text to highlight it in six colours with three modes (text colour, background, or both). Set a timer if you want a focused session. Export any entry as PDF, Markdown, or HTML when you need it somewhere else.

That's it. No accounts. No syncing. No analytics. No build step. No npm install. Just open the file and write.

## Features

**Writing.** Contenteditable editor with JetBrains Mono, terminal prompt styling, and automatic word count. Auto-saves as you type.

**Highlighting.** Select text and a colour bar appears. Six colours (gold, teal, red, blue, purple, yellow). Three modes: text colour only, background only, or both. Highlights persist across sessions and export correctly to all formats.

**Timer.** Optional. Leave the minutes blank for a stopwatch that counts up. Enter a number for a countdown. Session duration is recorded on the entry metadata.

**Dark/light mode.** Dark by default. Toggle with the theme button. Preference persists.

**Export.** Three options per entry:
- Print / Save as PDF (uses browser print dialog)
- Download as Markdown (.md with YAML frontmatter, highlight notation, session metadata)
- Download as HTML (standalone file with all styles and highlights preserved)

**Entries.** Sidebar lists all entries with date, time, and preview. Right-click to delete. Keyboard shortcuts: Cmd/Ctrl+N for new entry, Cmd/Ctrl+S for manual save.

**Storage.** Everything lives in localStorage. Plain HTML text is small. A 1,000-word entry with highlights is roughly 6KB. You can journal daily for years before approaching the browser's storage limit.

## Usage

Download `journal.html`. Open it in your browser. Start writing.

No server. No install. No configuration.

## Keyboard shortcuts

| Shortcut | Action |
|---|---|
| Cmd/Ctrl + N | New entry |
| Cmd/Ctrl + S | Save |

## Design

Built with JetBrains Mono for the editor and Cormorant Garamond for the chrome. Dark palette with gold accents. The visual language is intentionally terminal-like but the writing experience is soft, not rigid.

Part of the [UnArchived](https://unarchived.co) family of data-sovereign tools.

## License

MIT
