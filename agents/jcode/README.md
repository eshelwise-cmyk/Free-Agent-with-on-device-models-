# JCode

This repository tracks JCode as an agent option, but there are multiple unrelated projects using the name `jcode`. This page refers to the JCode project at `github.com/cnjack/jcode` unless another source is explicitly identified.

The referenced project describes a coding agent with plan mode, parallel teams, terminal/browser/desktop interfaces, SSH and Docker use, and OpenAI-compatible model APIs. Its README documents a quick installer and a setup wizard. Verify the upstream project before installing because project names can collide. 

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/cnjack/jcode/main/script/install.sh | sh
```

Source installation is also documented upstream and requires Go 1.22+, Node.js, and pnpm.

## First run

```bash
jcode
jcode doctor
```

The project documents `jcode doctor` for checking model and MCP connectivity.

## Models

JCode's documented model path is OpenAI-compatible APIs. This makes it suitable for local servers such as Ollama, LM Studio, or vLLM when their API compatibility matches the agent's requirements.

## Security

Review terminal, filesystem, browser, SSH, Docker, and MCP access before allowing an agent to act on important systems.

Official source: https://github.com/cnjack/jcode
