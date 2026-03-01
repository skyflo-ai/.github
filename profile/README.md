<p align="center">
  <a href="https://skyflo.ai">
    <img src="https://skyflo.ai/assets/hero.png" alt="Skyflo – Self-Hosted AI Control Layer for Kubernetes and CI/CD (Jenkins)" width="1000"/>
  </a>
</p>

<h3 align="center">Self-Hosted AI Control Layer for Kubernetes & CI/CD</h3>

<p align="center">
  <a href="https://skyflo.ai">Home</a> ·
  <a href="https://skyflo.ai/blog">Blog</a> ·
  <a href="docs/install.md">Installation</a> ·
  <a href="docs/architecture.md">Architecture</a>
</p>

---

[Skyflo](https://github.com/skyflo-ai/skyflo) is an AI operations agent for Kubernetes and CI/CD with native Jenkins support.

It converts natural language intent into typed, auditable tool execution inside your cluster.

Production changes require approval and are verified against original intent.

## Quick Start

Install Skyflo inside your Kubernetes cluster:

```bash
curl -fsSL https://skyflo.ai/install.sh | bash
```

See the full [installation guide](https://github.com/skyflo-ai/skyflo/blob/main/docs/install.md).

## Supported Tools

Skyflo currently integrates with: **Kubernetes**, **Helm**, **Argo Rollouts**, and **Jenkins**.

See the custom [MCP Server](https://github.com/skyflo-ai/skyflo/blob/main/mcp/README.md) for details.

## Execution Model

Skyflo enforces a deterministic control loop on every task:

**Plan → Execute → Diagnose → Propose → Apply → Verify**

* Diagnosis grounded in tool-returned evidence with confidence scoring
* Structured reasoning integrated into the agentic loop
* All mutating operations require approval enforced by the [Engine](https://github.com/skyflo-ai/skyflo/blob/main/engine/README.md)
* Full audit trail persistence

## Architecture

Skyflo consists of three primary components:

* **Engine**: FastAPI + LangGraph workflow enforcing deterministic execution and approval gating
* **MCP Server**: Typed tool interface for Kubernetes, Helm, Argo Rollouts, and Jenkins
* **Command Center**: Real-time UI with SSE streaming, reasoning visibility, and approval controls

See the [architecture guide](https://github.com/skyflo-ai/skyflo/blob/main/docs/architecture.md) for details.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Apache 2.0. See [LICENSE](LICENSE).

## Connect

<p>
  <a href="https://discord.gg/kCFNavMund">Discord</a> ·
  <a href="https://x.com/skyflo_ai">X</a> ·
  <a href="https://www.linkedin.com/company/skyflo">LinkedIn</a>
</p>
