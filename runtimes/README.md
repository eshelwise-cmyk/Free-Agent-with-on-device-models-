# Local model runtimes

Runtimes load and serve models. The agent is a separate layer.

Recommended mental model:

`Agent → API → Runtime → Model`

A runtime can expose a local or network API that an agent consumes. Compatibility depends on API shape, model architecture, tool calling, reasoning controls, context handling, and provider-specific behavior.

- [Ollama](ollama/README.md)
- [LM Studio](lm-studio/README.md)
- [vLLM](vllm/README.md)
- [OpenAI-compatible APIs](openai-compatible/README.md)
