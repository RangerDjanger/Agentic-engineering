# Agentic Engineering

Sample agents and skills demonstrating practical approaches to **Agentic Engineering** — building autonomous AI agents that perform complex software engineering tasks end-to-end.

---

## Table of Contents

| # | Name | Type | Description |
|---|------|------|-------------|
| 1 | [CodeDoc](agents/codedoc/) | Agent | Analyses any codebase and generates a Solution Architecture Document with UML 2.5.1 diagrams, interactive HTML report, and PDF export |

---

## What is Agentic Engineering?

Agentic Engineering is the practice of designing, building, and orchestrating **AI agents** that autonomously execute multi-step workflows — scanning codebases, reasoning about architecture, generating artifacts, and making decisions without human intervention at each step.

This repo contains real-world examples of agents and skills built for **GitHub Copilot CLI**, demonstrating patterns such as:

- **Multi-phase pipelines** — agents that scan, analyse, generate, and report in sequence
- **Tool orchestration** — agents that use file system tools, CLI commands, and external programs
- **Diagram generation** — producing UML-compliant Draw.io XML and Mermaid diagrams
- **Self-contained output** — generating complete HTML reports with embedded images and interactive features
- **Graceful degradation** — handling missing dependencies without failing

---

## Repository Structure

```
Agentic-Engineering/
├── agents/
│   └── codedoc/                ← Solution Architecture Documentation Agent
│       ├── codedoc.agent.md    ← Agent definition (install in Copilot)
│       ├── README.md           ← Documentation with screenshots
│       └── docs/screenshots/   ← Report screenshots
└── README.md                   ← You are here
```

---

## Getting Started

1. Browse the [Table of Contents](#table-of-contents) and pick an agent or skill
2. Follow the setup instructions in its README
3. Install the agent in your GitHub Copilot CLI environment
4. Invoke it and see agentic engineering in action

---

## Contributing

Have an agent or skill to share? Add it under `agents/` or `skills/` with a README and submit a PR.

## License

See [LICENSE](LICENSE) for details.
