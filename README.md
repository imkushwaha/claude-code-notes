# Claude Code · Field Notes

> An editorial-style, single-page reference for **Claude Code** — fifteen chapters of visual notes compiled from the [CampusX playlist](https://www.youtube.com/playlist?list=PLKnIA16_RmvaYH3poI0oJvbDF4zEvpq8W) by Nitish Singh.

[**→ View it live**](https://YOUR-USERNAME.github.io/claude-code-field-notes/) · Single HTML file · No build step · Mobile-friendly · Light & dark themes

---

## What this is

A self-contained HTML reference for learning agentic coding with Claude Code. Built as one file you can open in any browser — no backend, no build process, no dependencies. The structure follows Nitish Singh's CampusX playlist on Claude Code: fifteen chapters that trace the full arc from `claude` in a terminal to packaging your entire workflow as a shareable plugin.

Every concept gets a visual treatment. Every real artifact — slash commands, spec files, skills, sub-agents — is embedded with its full source as an expandable reference. Designed for active revision: jump to any chapter from the sidebar or the chapter index at the bottom; click any `Ch N` pill in the plugin composition stack to revisit the chapter where a concept was first introduced.

## What's inside

| Ch  | Title                    | Topic |
| --: | ------------------------ | ----- |
| 01  | Orientation              | From vibe to engineering — when AI-assisted coding fits |
| 02  | Installation             | Setting up `claude` in the terminal |
| 03  | The Vocabulary           | Slash commands, sessions, the three models |
| 04  | Practice                 | Making code changes that stick |
| 05  | The Constraint           | The 200k context window and how to spend it |
| 06  | The Most Important File  | `CLAUDE.md` as a persistent system prompt |
| 07  | Discipline               | Spec-driven development |
| 08  | Deliberation             | Plan Mode and Ultraplan |
| 09  | Codification             | Custom slash commands |
| 10  | Specialization           | Skills — turning Claude into a specialist |
| 11  | Delegation               | Sub-agents and isolated context |
| 12  | Orchestration            | Custom sub-agents, sequential and parallel |
| 13  | Connection               | MCP — everything outside the codebase |
| 14  | Enforcement              | Hooks — deterministic safeguards |
| 15  | Composition              | Plugins — the whole stack, packaged |

Eleven real-world artifacts are embedded as expandable references: three slash commands, three spec files, one skill, and four custom sub-agents — full source included for each.

## Features

- **Light and dark themes** — toggle in the top-right corner; preference persists across sessions
- **Collapsible sidebar** — toggle in the top-left; preference also persists
- **Chapter index** — full table of contents at the bottom of the page for quick navigation during revision
- **Embedded artifacts** — the real `.md` source for every command, spec, skill, and agent is included, collapsible by default
- **Mobile responsive** — sidebar slides as an overlay, grids collapse, no horizontal scroll
- **Custom visualizations per chapter** — a session-lifecycle event grid, a token-explosion chart, a sub-agent flow diagram, a plugin composition stack, and more
- **Zero build step** — pure HTML, CSS, and a small amount of vanilla JavaScript. Open in any modern browser.

## How to use it

**Online:** open the [live link](https://YOUR-USERNAME.github.io/claude-code-field-notes/) and read.

**Locally:** download `index.html` and open it in any modern browser. No server, no dependencies, no setup.

## Host your own copy

1. **Fork this repo** (or clone and push to your own GitHub account).
2. **Rename `claude-code-notes.html` to `index.html`** — GitHub Pages serves `index.html` at the root URL by default.
3. In your repo, go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch** → select **`main`** and **`/ (root)`** → click **Save**.
5. GitHub Pages will publish at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/` within a minute or two.

That's the entire deploy. No build, no CI, no config file.

## Credits

The notes content is adapted entirely from Nitish Singh's freely-published course.

- **Course author:** Nitish Singh
- **Channel:** CampusX (YouTube)
- **Source playlist:** [Claude Code (CampusX)](https://www.youtube.com/playlist?list=PLKnIA16_RmvaYH3poI0oJvbDF4zEvpq8W)

All technical credit and pedagogical structure belongs to Nitish. This repo is a visual-notes adaptation, intended for personal study and community learning.

## Built with

- A lot of help from [Claude](https://claude.ai)
- Typography: Fraunces (serif), JetBrains Mono (monospace), Inter Tight (sans) — all via Google Fonts
- Approximately zero lines of build configuration

## License

The code and markup are released under the **MIT License** — see [LICENSE](LICENSE).

The educational content is adapted from the CampusX playlist; its intellectual ownership remains with the original author. **If you fork or remix this work, please preserve attribution to Nitish Singh and keep the link to the original playlist intact.**

## Contact

Compiled by **Upendra Kumar** — *upendra.kumar48762@gamil.com*

Issues, suggestions, and pull requests welcome.

---
