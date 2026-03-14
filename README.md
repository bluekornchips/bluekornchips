# Bluekornchips

Platform and full-stack engineer. AWS, Kubernetes, Terraform in production. Bash-first tooling, CI/CD pipelines, and AI-assisted development workflows.

Never leaves home without bash, awk, grep, jq, and sed. If you can't test it, you can't prove it.

## Contact

- Email: [mail@tristank.ca](mailto:mail+removethisifyouarehuman@tristank.ca)
- GitHub: [@bluekornchips](https://github.com/bluekornchips)
- LinkedIn: [Tristan K](https://linkedin.com/in/tristank)

## Tech Stack

### DevOps & Infrastructure

![ArgoCD](https://img.shields.io/badge/-ArgoCD-blue?style=flat-square&logo=argocd&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-orange?style=flat-square&logo=amazonaws&logoColor=white)
![Concourse CI](https://img.shields.io/badge/-Concourse_CI-lightgreen?style=flat-square&logo=concourse&logoColor=white)
![Datadog](https://img.shields.io/badge/-Datadog-orange?style=flat-square&logo=datadog&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-blue?style=flat-square&logo=docker&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-yellow?style=flat-square&logo=elasticsearch&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-black?style=flat-square&logo=githubactions&logoColor=white)
![Helm](https://img.shields.io/badge/-Helm-blue?style=flat-square&logo=helm&logoColor=white)
![Kibana](https://img.shields.io/badge/-Kibana-blue?style=flat-square&logo=kibana&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-blue?style=flat-square&logo=kubernetes&logoColor=white)
![Logstash](https://img.shields.io/badge/-Logstash-orange?style=flat-square&logo=logstash&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-orange?style=flat-square&logo=rabbitmq&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-blue?style=flat-square&logo=terraform&logoColor=white)

### Development Tools

![Bun](https://img.shields.io/badge/-Bun-black?style=flat-square&logo=bun&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude_Code-purple?style=flat-square&logo=claude&logoColor=white)
![Cursor](https://img.shields.io/badge/-Cursor-blue?style=flat-square&logo=cursor&logoColor=white)
![ngrok](https://img.shields.io/badge/-ngrok-1F1E37?style=flat-square&logo=ngrok&logoColor=white)
![NextJS](https://img.shields.io/badge/-NextJS-black?style=flat-square&logo=next.js&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-EE4C2C?style=flat-square&logo=ollama&logoColor=white)
![React](https://img.shields.io/badge/-React-blue?style=flat-square&logo=react&logoColor=white)
![Slack API](https://img.shields.io/badge/-Slack_API-4A154B?style=flat-square&logo=slack&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-purple?style=flat-square&logo=vite&logoColor=white)

## Skills & Expertise

### Languages

![Bash](https://img.shields.io/badge/-Bash-black?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/-C-blue?style=flat-square&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/-Csharp-blue?style=flat-square&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-yellow?style=flat-square&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-blue?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-blue?style=flat-square&logo=typescript&logoColor=white)

## Projects

### [Zangarmarsh](https://github.com/bluekornchips/zangarmarsh), Shell Profile Automation

Shell profile automation for Bash and Zsh with prompt enhancements, platform detection, and development tooling.

Highlights:

- Cross-shell profile setup with Git branch and Kubernetes context prompts
- Path management with deduplication and platform-specific logic
- SSH agent setup with helpers for NVM and Python virtual environments
- Quest Log tool that generates Cursor rules and commands from JSON schema
- Trilliax cleanup tool that removes generated files and build artifacts
- Hearthstone save/restore tool for shell state snapshots
- Ice Block emergency shell recovery
- Talent Calculator for skill tracking

### [Send to Slack](https://github.com/bluekornchips/send-to-slack), Slack Block Kit CLI Tool

Bash program designed to send block kit content to Slack via the Slack Web API. Lightweight, cross-platform tool for multi-language projects that need feature parity without language-specific dependencies.

Highlights:

- Slack Block Kit support with native and keyed formats from stdin or file
- File uploads with automatic image or rich-text block creation
- Crossposting with permalinks and thread replies
- Input flexibility: stdin, files, or embedded JSON
- Dry-run mode, health checks, and debug logging
- Concourse CI resource type support for pipeline notifications

### [Gandalf](https://github.com/bluekornchips/gandalf), MCP Server for Agentic Tools

MCP 2025-06-18 compliant server that aggregates conversation history from Cursor and Claude Code for AI-assisted development.

Highlights:

- JSON-RPC MCP server with tool registry and query tools
- Conversation recall with keyword search and export
- CLI for install, server control, and registry management

### [TellMeAboutATimeWhen](https://github.com/bluekornchips/TellMeAboutATimeWhen), Git Commit Analyzer

Bash tool that analyzes Git commits by repository, branch, and author with optional GitHub PR detail output.

Highlights:

- Date range filters with single date or range
- Paginated output files with commit details and changed files
- Optional GitHub integration via gh and jq
- JIRA ticket extraction via Atlassian CLI for commits that reference ticket IDs

### [auryouready](https://github.com/bluekornchips/auryouready), User AUR Packages

Workspace for user-specific AUR-style packages. Each package has its own folder with a PKGBUILD and helpers for local builds or sharing.

Highlights:

- Repacks: Cursor IDE, Google Chrome, Signal Desktop, Synology Drive Client
- shfmt source build and examples/hello-world starter template
- Redirect build artifacts via PKGDEST/SRCDEST/LOGDEST/BUILDDIR for clean output
