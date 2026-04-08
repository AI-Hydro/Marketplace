# AI-Hydro Marketplace

Static MCP server catalog for the [AI-Hydro](https://github.com/AI-Hydro/AI-Hydro) platform.

Served via GitHub Pages at `https://ai-hydro.github.io/Marketplace/api/`.

## API Endpoints

| Endpoint | Description |
| --- | --- |
| `GET /api/marketplace.json` | Browse all available MCP servers |
| `GET /api/download/{mcpId}.json` | Get install details for a specific server |

## Adding a Server

To add your MCP server to the marketplace:

1. Fork this repo
2. Add your server entry to `api/marketplace.json`
3. Create `api/download/{your-mcp-id}.json` with install details
4. Submit a pull request

See [AI-Hydro Contributing Guide](https://github.com/AI-Hydro/AI-Hydro/blob/main/CONTRIBUTING.md) for details.
