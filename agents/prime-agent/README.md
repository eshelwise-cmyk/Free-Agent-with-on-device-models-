# Prime Agent

Prime Agent is a coding and research harness built around persistent sessions, recursive subagents, executable skills, and long-running tasks.

## Install

macOS and Linux:

```bash
curl -fsSL https://app.primeintellect.ai/prime-agent/install.sh | sh
```

Then run it from the project directory:

```bash
cd /path/to/project
prime-agent
```

Source installation is documented upstream and currently requires Node.js 22.8.0 or newer.

## Models and providers

Prime Agent supports provider connections and custom OpenAI-compatible providers. Its documentation specifically covers Ollama, LM Studio, vLLM, and other compatible APIs. Provider compatibility settings may be needed for differences in developer-role or reasoning-effort support.

## Skills and agents

Prime Agent supports executable skills, recursive subagents, persistent sessions, background execution, and long-running workflows. Treat skills and extensions as code that can affect the project and system.

## Security

Prime Agent's documentation states that generated Python and project commands execute with the user's permissions and that its worker/kernel processes are not a security sandbox. Use a disposable clone, clean worktree, checkpoint, or external sandbox for untrusted work.

Official source: https://github.com/PrimeIntellect-ai/prime-agent
