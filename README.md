# 🧠 Claude Skills & MCP Tooling Collection

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-Ready-purple?style=flat-square)](https://modelcontextprotocol.io/)
[![Agentic AI](https://img.shields.io/badge/Agentic_AI-Claude-coral?style=flat-square)](https://anthropic.com/)

> Curated toolkit of custom Model Context Protocol (MCP) servers, tool schemas, and specialized agent skills to extend Claude Code and LLM capabilities in automated development workflows.

---

## 🔧 Skills & Modules Included

- **DevOps & Workspace Automation:** Shell script orchestration, repo status, and automated file pipelines.
- **Research & Inspection:** Source tree parsing, structural code analysis, and dependency inspection.
- **Agentic Workflow Integrations:** Specialized task delegators and prompt chaining primitives.

---

## 🚀 Usage with Claude Desktop / CLI

Add the server configurations into your `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "claude-skills": {
      "command": "python",
      "args": ["path/to/claude-skills-collection/main.py"]
    }
  }
}
```

---

## 👨‍💻 Maintainer
**Syed Mesum Ali** - [@mesumali-dev](https://github.com/mesumali-dev)
