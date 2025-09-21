<h1 align="center">
  <a href="https://skyflo.ai">
    <img src="https://skyflo.ai/images/logo_wide.png" alt="Skyflo.ai Logo" width="640">
  </a>
</h1>

<h3 align="center">Your DevOps Copilot: Kubernetes, Jenkins, and More</h3>

Skyflo.ai is an AI co‑pilot for Cloud & DevOps that unifies Kubernetes operations and CI/CD systems (starting with Jenkins) behind a natural‑language interface with a safety‑first, human‑in‑the‑loop design. Instead of memorizing CLI commands or clicking through UIs, just tell Skyflo what you want in natural language.

### 💡 What it can do

#### Troubleshoot fast

```text
Show me the last 200 lines of logs for checkout in production. If there are errors, summarize them.
```

#### Safer rollouts and rollbacks

```text
Progressively canary rollout auth-backend in dev through 10/25/50/100 steps
```

#### Jenkins at conversational speed

```text
Trigger backend/build with BRANCH=release/2025-09 and ENV=staging. Poll for logs and let me know if something goes wrong.
```

### 🎯 Who is Skyflo.ai for?

Skyflo.ai is purpose-built for:

- **DevOps Engineers**
- **Cloud Architects**
- **IT Managers**
- **SRE Teams**
- **Security Professionals**

### 🚀 Key Features

- **Unified AI Copilot**: One agent for K8s, Jenkins, Helm, and Argo Rollouts
- **Human-in-the-loop Design**: Approval required for any mutating operation
- **Plan → Execute → Verify**: Iterative loop where the agent keeps going untill the task is done 
- **Real-time Streaming**: Everything that the agent does is streamed to the UI in real time
- **MCP-based tool execution**: Standardized tools for safe, consistent actions
- **Built for Teams**: Manage teams, integrations, rate limiting and much more

## ⚡ Quick Start

Install Skyflo.ai in your Kubernetes cluster using a single command:

```bash
curl -sL https://raw.githubusercontent.com/skyflo-ai/skyflo/main/deployment/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```

See the [Installation Guide](https://github.com/skyflo-ai/skyflo/blob/main/docs/install.md) for details.

### 🛠️ Supported Tools

- **Kubernetes**: Resource discovery; get/describe; logs/exec; safe apply/diff flows
- **Jenkins**: Jobs, builds, logs, SCM info
- **Argo Rollouts**: Inspect status; pause/resume; promote/cancel; analyze delivery
- **Helm**: Search, install/upgrade/rollback with dry-run and diff-first safety

### 🧩 Components

- **Engine**: FastAPI + LangGraph workflow with approvals and SSE streaming
- **MCP Server**: FastMCP tools for `kubectl`, `argo` (Rollouts), `helm`, `jenkins`
- **Command Center (UI)**: Next.js UI written in TypeScript and designed using Tailwind

Refer to the [architecture](https://github.com/skyflo-ai/skyflo/blob/main/docs/architecture.md) for more details.

### 🤝 Contributing

Join the mission to build the future of AI in DevOps! Whether you're fixing bugs, improving documentation, or proposing new features, your contributions are very much appreciated.

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/issue-number-description`
3. **Commit** your changes: `git commit -m 'feat: add amazing feature'`
4. **Push** to the branch: `git push origin feature/issue-number-description`
5. **Submit** a pull request

Please follow our [contributing guidelines](https://github.com/skyflo-ai/skyflo/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/skyflo-ai/skyflo/blob/main/CODE_OF_CONDUCT.md).

### 🌐 Community

- Join our [Discord](https://discord.gg/kCFNavMund) server
- Follow us on [X](https://x.com/skyflo_ai)
- Subscribe to our [YouTube](https://www.youtube.com/@skyfloai) channel
- Read our [blog](https://skyflo.ai/blog) for the latest updates

## 📚 Resources

- [Installation Guide](https://github.com/skyflo-ai/skyflo/blob/main/docs/install.md)
- [Architecture](https://github.com/skyflo-ai/skyflo/blob/main/docs/architecture.md)
- [Website](https://skyflo.ai)

## 📄 License

Skyflo.ai is open source and licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
