# Install an agent

Use the project's official installer or package method first. Avoid third-party installers unless the project itself recommends them.

## OpenCode

```bash
curl -fsSL https://opencode.ai/install | bash
```

OpenCode also documents package-manager, Docker, and release-binary methods.

## JCode

For the `cnjack/jcode` project:

```bash
curl -fsSL https://raw.githubusercontent.com/cnjack/jcode/main/script/install.sh | sh
```

## Prime Agent

```bash
curl -fsSL https://app.primeintellect.ai/prime-agent/install.sh | sh
```

Then:

```bash
prime-agent
```

## SuperAGI

Use the current installation instructions in the official SuperAGI repository and documentation. Do not assume older Docker or Python instructions remain current.

## General rule

After installation, run the project's version or diagnostic command and verify the binary before connecting models or tools.
