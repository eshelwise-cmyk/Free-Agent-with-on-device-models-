# Security

Running a model locally does not make an agent safe. The model can still produce commands or instructions that an agent executes with the permissions granted to it.

## Before enabling tools

- Use a disposable project for first tests.
- Keep secrets outside the project when possible.
- Do not expose private API keys to prompts or model context.
- Review filesystem permissions.
- Review shell/terminal permissions.
- Review network access.
- Review browser access.
- Review MCP servers and their permissions.
- Prefer sandboxed execution for untrusted code.
- Keep backups or use version control before autonomous changes.

## MCP

An MCP server is software, not just a prompt. Treat it as a program with whatever permissions its configuration gives it. Read its source or trusted documentation before connecting it to sensitive data.

## Command execution

Do not automatically approve commands you do not understand. Be especially careful with commands that delete files, modify system configuration, install software, expose network services, or access credentials.

## Credentials

Use the narrowest credentials possible. Prefer environment-specific keys with limited permissions. Never commit API keys, tokens, cookies, private keys, or passwords to the repository.

## Local versus cloud

Local inference can reduce the need to send prompts to a remote provider, but local agents may still make network requests through tools, MCP servers, package managers, browsers, or APIs. Inspect the whole workflow, not just where the model runs.
