# Claude Code Guide Plugin

A comprehensive guide plugin for Claude Code CLI, Claude Agent SDK, and Claude API, especially helpful for skill creators.


## Features

- Get instant help with Claude Code CLI features and configuration
- Learn about the Claude Agent SDK for building custom agents
- Understand the Claude API for direct model interaction
- Access official documentation with actionable guidance

## Installation

```bash
claude plugin add leepokai/claude-code-guide
```

## Usage

### Commands

| Command | Description |
|---------|-------------|
| `/claude-code-guide:guide` | Get help with Claude Code CLI, Agent SDK, or API |
| `/claude-code-guide:docs` | Fetch and browse Claude Code documentation |
| `/claude-code-guide:sdk` | Get help specifically with Claude Agent SDK |
| `/claude-code-guide:api` | Get help specifically with Claude API |

### Skills

The plugin includes a `guide` skill that automatically activates when you ask questions about:
- Claude Code CLI features, hooks, settings, MCP servers
- Claude Agent SDK configuration and usage
- Claude API endpoints and integrations

### Agent

The `claude-code-guide` agent is available for in-depth research and guidance. It will:
- Fetch official documentation
- Provide actionable guidance
- Include code examples
- Reference specific documentation URLs

## Topics Covered

### Claude Code CLI
- Installation and configuration
- Hooks and custom skills
- MCP server configuration
- IDE integrations (VS Code, JetBrains)
- Settings and keyboard shortcuts
- Subagents and plugins
- Sandboxing and security

### Claude Agent SDK
- SDK overview (Node.js/TypeScript, Python)
- Agent configuration
- Custom tools
- Session management
- Permissions
- MCP integration
- Hosting and deployment
- Cost tracking
- Context management

### Claude API
- Messages API
- Streaming
- Tool use
- Vision and PDF support
- Citations
- Extended thinking
- MCP connector
- Cloud provider integrations (Bedrock, Vertex AI)

## Documentation Sources

- Claude Code: https://code.claude.com/docs/
- Claude Platform: https://platform.claude.com/

## License

MIT
