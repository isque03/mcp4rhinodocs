# Documentation project instructions

## About this project

- Public **end-user** docs for **MCP4Rhino** (Rhino 8 plugin + local MCP server)
- Built on [Mintlify](https://mintlify.com); pages are MDX with YAML frontmatter
- Configuration lives in `docs.json`
- Product source: https://github.com/isque03/mcp4rhino
- Auto-deploys on push when connected to Mintlify

## Terminology

- **MCP4Rhino** — the Rhino plugin and product name
- **MCP** — Model Context Protocol
- **Status** — the MCP4Rhino Status dialog (`MCP4RhinoStatus` / `MCP4RhinoStatusUI`)
- Default endpoint: `http://127.0.0.1:4010/mcp` (port **4010**)
- Menu: Windows under **Tools**; macOS **top-level MCP4Rhino** menu

## Style preferences

- Write for end users (architects, designers, students) — not plugin developers
- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Status…**
- Code formatting for commands, paths, tool names, and env vars
- Diataxis: tutorials learn, how-tos do, reference lists facts
- Never invent ports other than 4010 / `MCP4RHINO_PORT`

## Content boundaries

- In scope: install (Package Manager / release `.yak`), connect Claude/Cursor, Status, troubleshoot, report issues, commands/config/tools reference
- Out of scope: hot-reload, install-from-source, host/Tools/Logic internals, CI/publish runbooks, legal/compliance disclaimers on the landing page — keep contributor material in the product repo
