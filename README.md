# spore.host Scoop Bucket

Official Scoop bucket for [spore.host](https://spore.host) — tools for launching and managing ephemeral AWS EC2 instances on Windows.

## Available manifests

| App | Description |
|-----|-------------|
| `truffle` | Find EC2 instance types, compare spot prices, check quotas |
| `spawn` | Launch and manage EC2 instances with automatic lifecycle management |
| `lagotto` | Watch for EC2 capacity and act when it appears |
| `spore-host-mcp` | MCP server for AI assistants (Claude, Cursor) |

## Installation

```powershell
# Add the bucket
scoop bucket add spore-host https://github.com/spore-host/scoop-bucket

# Install a tool
scoop install truffle
scoop install spawn
scoop install lagotto
scoop install spore-host-mcp
```

## Documentation

Full documentation at [spore.host](https://spore.host).

## Automated updates

Manifests are updated automatically via GoReleaser when each tool publishes a new release.

## License

Apache 2.0 — Copyright 2025-2026 Scott Friedman.
