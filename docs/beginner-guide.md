# Beginner guide

## The five layers

1. **Agent**: the application that plans and performs work.
2. **Model**: the language or multimodal model generating decisions.
3. **Runtime**: software that loads and serves a local model.
4. **Tools**: terminal, files, browser, code execution, APIs, and MCP.
5. **Hardware/cloud**: where the model and tools actually run.

## Easiest local path

```text
Install a runtime
        ↓
Download a small compatible model
        ↓
Test the model directly
        ↓
Install an agent
        ↓
Connect the agent to the runtime
        ↓
Add only the tools you need
        ↓
Test in a disposable project
```

Start with a small model and a narrow task. Increase model size, context, or tool access only when the task requires it.

## If something fails

Check the runtime first, then the API endpoint, then the model identifier, then the agent configuration, then tool compatibility.
