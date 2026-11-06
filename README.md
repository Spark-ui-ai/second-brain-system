# Second Brain — AI-Powered Personal Knowledge System

An AI-powered personal knowledge base that combines **Obsidian** (local-first, markdown-based notes) with **Claude** to organize, interlink, and retrieve information — turning scattered notes into a queryable wiki.

> Built on the idea of a "second brain": capture raw information once, let the system structure and connect it, and retrieve insights on demand.

## Architecture — Three Layers

| Layer | Tool | Role |
| --- | --- | --- |
| Knowledge base | Obsidian (markdown files) | The "codebase" — a growing library of interconnected notes |
| Organizer | Claude (AI) | The "programmer" — structures raw notes, generates cross-links, summaries, and connections |
| Query layer | Obsidian wiki-links + search | The interface — ask questions and pull insights out of the wiki |

**The feedback loop:** raw notes go in → AI organizes and links them → connected insights come out.

## Why Obsidian + Claude?

- **Local-first & future-proof:** everything is plain markdown files stored locally. If any app disappears tomorrow, the knowledge remains mine.
- **Cross-linking:** notes connect with `[[double brackets]]`, forming a network of ideas — visualized in Obsidian's graph view.
- **AI as a librarian:** Claude processes raw dumps (lecture notes, articles, ideas) into structured, linked, searchable pages — on autopilot.

## How I Use It

1. **Capture** — dump lecture notes, study summaries, article highlights, and project ideas as raw markdown.
2. **Process** — feed unstructured notes to Claude → it structures them, extracts key points, and suggests links to existing notes.
3. **Connect** — add `[[wiki-links]]` between related concepts; the graph view shows how ideas relate.
4. **Retrieve** — query the wiki during revision, project work, or writing.

## What's in the Vault (Examples)

- Semester notes (Linear Algebra, Programming, Physics) cross-linked by concept
- Project ideas and research bookmarks with AI-generated summaries
- Study guides distilled from raw class notes

## Tech / Tools

- **Obsidian** — local markdown knowledge base
- **Claude** (Projects) — AI structuring, linking, and summarization
- **Markdown** — universal, portable format

## Roadmap

- [ ] Build dedicated project templates for consistent note structure
- [ ] Automate the AI structuring step with scripts
- [ ] Add spaced-repetition review prompts for exam prep
- [ ] Publish selected parts of the wiki as a public knowledge resource

## What I Learned

- Personal knowledge management (PKM) principles: capture → organize → retrieve
- Prompt engineering for structuring and interlinking unstructured text
- Local-first tooling: keeping data ownership while using AI

## Author

**Kunal Sharma** — B.E. CSE @ Chandigarh University
- GitHub: [Spark-ui-ai](https://github.com/Spark-ui-ai)
- LinkedIn: [Kunal Sharma](https://www.linkedin.com/in/kunal-sharma-8662a7306)
