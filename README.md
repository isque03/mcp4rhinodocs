# MCP4Rhino docs

End-user Mintlify documentation for [MCP4Rhino](https://github.com/isque03/mcp4rhino).

## Local preview

```bash
npx mintlify dev
```

## Deploy

Push to `main`. Mintlify auto-deploys when this GitHub repo is connected in the Mintlify dashboard.

## Structure (Diataxis)

| Path | Quadrant |
|------|----------|
| `index.mdx`, `quickstart.mdx` | Intro + tutorial |
| `howto/*` | Connect, troubleshoot, report issues |
| `reference/*` | Commands, config, MCP tools |
| `grasshopper/*` | Alpha overview, installation/testing how-to, array tutorial, and tool reference |

Contributor playbooks stay in the product repo, not this site.

## Grasshopper alpha documentation

Grasshopper 1 support is experimental in MCP4Rhino **0.6.0-alpha**. Native runtime validation is assigned to licensed testers; stable users can stay on **0.5.3**.

- [Capabilities and limits](grasshopper/overview.mdx)
- [How to install and test the alpha](grasshopper/install-alpha.mdx)
- [Build your first parametric array](grasshopper/first-definition.mdx)
- [Grasshopper tool reference](grasshopper/tools.mdx)
