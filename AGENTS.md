# Documentation project instructions

## About this project

- Public docs site for **MCP4Rhino** (Rhino 8 plugin + local MCP server)
- Built on [Mintlify](https://mintlify.com); pages are MDX with YAML frontmatter
- Configuration lives in `docs.json`
- Product source of truth: https://github.com/isque03/mcp4rhino
- This repo (`mcp4rhinodocs`) is the Mintlify deploy target (auto-deploy on push)

## Terminology

- **MCP4Rhino** — product / Rhino package name (not "MCP for Rhino")
- **Endpoint** — default `http://127.0.0.1:4010/mcp`
- **Host** — the `.rhp` plugin (commands, HTTP, RUI)
- **Tools / Logic** — hot-reloadable MCP tool assemblies
- **Status** — Status dialog / `MCP4RhinoStatus` / `MCP4RhinoStatusUI`
- Menu: Windows **Tools → MCP4Rhino**; macOS top-level **MCP4Rhino**

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Do not invent ports other than **4010** (unless documenting `MCP4RHINO_PORT`)
- Code checks are **findings only** — never claim legal compliance or an RA stamp
- Follow Diataxis: tutorials teach, how-tos accomplish a task, reference lists facts, explanation covers why

## Content boundaries

- End-user install, connect, troubleshoot, and tool/command reference belong here
- Deep contributor playbooks (`CLAUDE.md`, CI publish runbooks) stay in the product repo; link out when needed
- Do not document unpublished internal admin tooling
