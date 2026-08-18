# Free Agents with On-Device Models

A practical guide to open-source AI agents, local and open-weight models, model runtimes, skills, MCP, hardware selection, and safe agent setup.

The goal is simple: help you go from **device → runtime → model → agent → tools** without assuming that a larger model or more software is automatically better.

## Included agents

- [OpenCode](agents/opencode/README.md)
- [JCode](agents/jcode/README.md)
- [Prime Agent](agents/prime-agent/README.md)
- [SuperAGI](agents/superagi/README.md)

## Local model runtimes

- [Ollama](runtimes/ollama/README.md)
- [LM Studio](runtimes/lm-studio/README.md)
- [vLLM](runtimes/vllm/README.md)
- [OpenAI-compatible APIs](runtimes/openai-compatible/README.md)

## Model families

- [GLM](models/glm/README.md)
- [DeepSeek](models/deepseek/README.md)
- [Qwen](models/qwen/README.md)
- [Other open-weight models](models/other-open-models.md)
- [Model sizing](models/model-sizing.md)
- [Hardware guide](models/hardware-guide.md)

## Start here

1. [Beginner guide](docs/beginner-guide.md)
2. [Choose a model](workflows/choose-a-model.md)
3. [Choose local vs cloud](workflows/choose-local-vs-cloud.md)
4. [Connect an agent to a model](workflows/connect-agent-to-model.md)
5. [Build a local agent stack](workflows/build-local-agent-stack.md)
6. [Read the security guide](docs/security.md)

## Important

Local inference does not automatically make an agent safe. Agents that can execute commands, modify files, browse the web, or call MCP tools may act with the permissions available to the user. Review permissions, credentials, network access, and sandboxing before giving an agent access to important data or systems.

## Sources and attribution

This repository is a curated guide to third-party projects. Each project remains the property of its authors. Installation commands, licenses, and capabilities should be verified against the project's official documentation before use. Adapted material must follow the original project's license and attribution requirements.
