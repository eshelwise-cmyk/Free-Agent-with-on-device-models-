# Build a local agent stack

A simple stack is:

```text
Agent
  ↓
OpenAI-compatible API
  ↓
Ollama / LM Studio / vLLM
  ↓
Local model
  ↓
CPU / GPU / unified memory
```

## Recommended setup process

1. Pick one agent: OpenCode, JCode, Prime Agent, or another suitable project.
2. Pick one runtime.
3. Pick one model that fits the device.
4. Test the model without the agent.
5. Connect the agent.
6. Add one tool at a time.
7. Add MCP only when a real task needs it.
8. Record the working model, runtime, and configuration.
9. Keep the stack reproducible with notes or configuration files that do not contain secrets.

Avoid adding several agents, runtimes, and MCP servers at once. When something breaks, a small stack is much easier to debug.
