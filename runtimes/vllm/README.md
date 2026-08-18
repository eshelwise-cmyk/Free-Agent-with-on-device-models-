# vLLM

vLLM is a high-throughput inference and serving engine. It is especially useful when you want a model server that exposes an API for other applications.

Typical workflow:

1. Install vLLM using its current official documentation.
2. Choose a model supported by the installed version.
3. Confirm GPU and memory requirements.
4. Start the model server.
5. Point the agent at the server's supported API endpoint.

For local desktop use, Ollama or LM Studio may be simpler. For dedicated GPU servers and higher-throughput workloads, vLLM is often a better fit.

Official repository: https://github.com/vllm-project/vllm
