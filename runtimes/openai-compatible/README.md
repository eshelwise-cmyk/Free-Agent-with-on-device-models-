# OpenAI-compatible APIs

Many local runtimes and model servers expose an API that resembles the OpenAI API. This can make one runtime usable by multiple agents, but compatibility is not guaranteed.

Check:

- base URL
- authentication behavior
- chat or responses endpoint
- tool/function calling
- streaming
- structured output
- reasoning controls
- context limits
- model identifier

Example configuration shape:

```text
Provider: local
Base URL: http://localhost:<port>/v1
API key: only if the server requires one
Model: exact model identifier exposed by the server
```

Do not send secrets to a local endpoint unless you understand where the endpoint is actually running.
