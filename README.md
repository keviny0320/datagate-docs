# Datagate Documentation

Developer documentation for [Datagate](https://getdatagate.com) — the data marketplace for AI agents.

Published at [docs.getdatagate.com](https://docs.getdatagate.com).

## Local Development

Install [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Run the docs locally:

```bash
mintlify dev
```

## Structure

```
introduction.mdx          — What is Datagate
quickstart.mdx             — First query in 5 minutes
authentication.mdx         — API keys and JWT
concepts.mdx               — Datasets, connectors, pricing

sdk/python/                — Python SDK reference
sdk/typescript/            — TypeScript SDK reference
mcp/                       — MCP integration guides
guides/                    — Deep-dive guides (filters, multi-dataset, costs)
api-reference/             — REST API reference
```
