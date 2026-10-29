# Roadmap — downloads

Public distribution for **Roadmap**. Built from the (private)
Roadmap monorepo and published here. Documentation: <https://docs.roadmap-mcp.com/>.

## Roadmap Pro

[Download `install/roadmap-pro.zip`](https://raw.githubusercontent.com/roadmap-mcp/roadmap-dist/main/install/roadmap-pro.zip)
— version `0.2.0-SNAPSHOT`.

Requires Python 3.13+ on your PATH. Unzip anywhere and run `start.bat` (Windows) or
`bash start.sh` (macOS/Linux). The first run sets up a local environment and installs
the bundled plugins, which takes a few minutes; then the app is at
<http://localhost:8090>. MCP clients connect over SSE at
`http://127.0.0.1:8090/mcp/sse`.

## Roadmap Lite

To be released soon.

## Plugins

- [`registry/pro.json`](registry/pro.json) — the plugins published for Pro; the app's
  Settings → System → Admin installs the ones not bundled (such as Trello) from here.
- `plugins/*.whl` — the plugin wheels.

## Knowledge base packs

- [`kb-packs/index.json`](kb-packs/index.json) — ready-made personas and node types;
  the app's Settings → Knowledge Base → Layer 2 installs them (Browse packs).
