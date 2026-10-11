# MCP4Rhino docs

Mintlify documentation for [MCP4Rhino](https://github.com/isque03/mcp4rhino).

Push to `main` to trigger Mintlify auto-deploy (when the site is linked in the Mintlify dashboard).

## Local preview

```bash
npm i -g mint
cd mcp4rhinodocs
mint dev
```

Open the URL printed by the CLI (usually `http://localhost:3000`).

Legacy alias: `npx mintlify dev` if you still use the older package name.

## Structure (Diataxis)

| Path | Quadrant |
|------|----------|
| `index.mdx`, `quickstart.mdx` | Intro + tutorial |
| `guides/*` | How-to |
| `reference/*` | Reference |
| `explanation/*` | Explanation |

## Product repo

Source, Yak package, and contributor docs: https://github.com/isque03/mcp4rhino
