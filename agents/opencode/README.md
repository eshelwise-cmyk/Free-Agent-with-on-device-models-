# OpenCode

OpenCode is an open-source AI coding agent available as a terminal interface, desktop app, and IDE extension. Current official documentation supports multiple installation methods and provider connections. citeturn0search1turn0search14

## Install

```bash
curl -fsSL https://opencode.ai/install | bash
```

Other documented methods include npm, Bun, pnpm, Yarn, Homebrew, Arch Linux packages, Windows package managers, Docker, and release binaries. Check the official documentation before choosing a platform-specific method. citeturn0search1

## Models

OpenCode can connect to supported providers and custom providers. Use `/connect` for supported integrations or configure a provider when needed. citeturn0search14

For local inference, see [runtime setup](../../runtimes/README.md) and [connecting an agent to a model](../../workflows/connect-agent-to-model.md).

## MCP

OpenCode supports local and remote MCP servers. MCP tools become available to the model after configuration. Enable only the tools you need because MCP tool descriptions consume context. citeturn0search11

## Security

Treat coding-agent tools as privileged. Review file, terminal, network, and MCP permissions before use, especially in repositories containing credentials or sensitive data.

Official sources: [OpenCode documentation](https://opencode.ai/docs) and [OpenCode GitHub](https://github.com/anomalyco/opencode).
