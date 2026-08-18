# Compatibility matrix

This table is a template for verified compatibility. Do not mark a combination as supported solely because both projects expose an OpenAI-like API.

| Agent | Ollama | LM Studio | vLLM | OpenAI-compatible API | MCP | Local models |
|---|---|---|---|---|---|---|
| OpenCode | verify current docs | verify current docs | verify current docs | yes, with provider configuration | yes | yes, when provider/runtime is compatible |
| JCode | verify exact release | verify exact release | verify exact release | documented | documented | depends on API/runtime |
| Prime Agent | documented | documented | documented | documented | documented | documented |
| SuperAGI | verify current project docs | verify current project docs | verify current project docs | verify current project docs | verify current project docs | verify current project docs |

`documented` means the upstream project currently describes the integration. `verify current docs` means this guide intentionally does not guess.

Compatibility can change with agent releases, model releases, API implementations, and runtime versions. Record the exact versions when troubleshooting.
