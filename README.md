# Abishai James

IT and infrastructure since 2005, New York. I build small, well tested services and write the docs so somebody else can run them.

I build with AI tools and say so. I read everything before it ships and it's my name on it when it breaks.

### Civic data servers

MCP servers that let an LLM client read public records. For tenant organizers, legal aid, and people representing themselves.

| | |
|---|---|
| [mcp-nychousing](https://github.com/haksanlulz/mcp-nychousing) | NYC HPD violations, complaints, building ownership, litigation, marshal evictions · `npx @haksanlulz/mcp-nychousing` |
| [mcp-courtwatch](https://github.com/haksanlulz/mcp-courtwatch) | US case law and court dockets via CourtListener · `npx @haksanlulz/mcp-courtwatch` |
| [mcp-fairrent](https://github.com/haksanlulz/mcp-fairrent) | HUD Fair Market Rents and Section 8 income limits · `npx @haksanlulz/mcp-fairrent` |
| [mcp-wagewatch](https://github.com/haksanlulz/mcp-wagewatch) | DOL wage and hour enforcement records · `npx @haksanlulz/mcp-wagewatch` |

### Other work

**[GUDBUS](https://github.com/haksanlulz/GUDBUS)** · a GURPS 4e Discord service running in production for a live community. ~21K lines of application code, 3,154 passing tests, 106 commands, test gated CI, and a startup check that won't boot against a stale database schema.

**[label-assay](https://github.com/haksanlulz/label-assay)** · checks alcohol labels against TTB 27 CFR and cites the regulation on every finding. [Live demo](https://haksanlulz-label-assay.hf.space).

**[mcp-chat](https://github.com/haksanlulz/mcp-chat)** · a testbed that drives MCP servers with a real model in the loop. Found three bugs in the civic servers that their test suites missed.
