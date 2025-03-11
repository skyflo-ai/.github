<h1 align="center">
  <a href="https://skyflo.ai">
    <img src="https://skyflo.ai/images/logo_wide.png" alt="Skyflo.ai Logo" width="640">
  </a>
</h1>

<h3 align="center">AI-Powered Natural Language Management for AWS and Kubernetes</h3>

<p align="center">
  Skyflo.ai enables cloud engineers to use natural language to manage, monitor, and optimize their cloud infrastructure.
</p>

<p align="center">
  <a href="https://github.com/skyflo-ai/skyflo">Get Started</a> •
  <a href="https://github.com/skyflo-ai/skyflo/tree/main/docs">Documentation</a> •
  <a href="https://skyflo.ai/community">Community</a> •
  <a href="https://skyflo.ai/blog">Blog</a> •
  <a href="https://skyflo.ai/demo">Live Demo</a>
</p>

---

## ✨ What is Skyflo.ai?

Skyflo.ai is an AI-powered platform for cloud management that enables users to create intelligent agents for AWS and Kubernetes environments. Instead of memorizing complex CLI commands or navigating console UIs, simply tell Skyflo what you want to do in natural language.

Skyflo.ai follows an open-core business model with both community and enterprise offerings:

- **Community Edition**: Free, open-source core functionality
- **Enterprise Edition**: Premium features with enhanced security, compliance, and multi-cloud capabilities

## 🚀 Key Features

- **Natural Language Interface**: Manage cloud resources using simple English commands
- **Intelligent Agents**: Purpose-built agents for AWS and Kubernetes environments
- **Safe Operations**: Read-only mode by default, with opt-in write permissions
- **CLI Integration**: Generate and execute AWS/kubectl commands automatically
- **Decision Routing**: Intelligent workflow routing for creating, updating, deleting, and fetching resources
- **Enterprise Grade**: Built for security, compliance, and scale

## 🧠 How It Works

1. User submits a natural language query
2. Query is classified by decision type (create, update, delete, fetch)
3. Appropriate workflow is triggered based on the decision
4. The system generates the required AWS/kubectl commands
5. Commands are executed based on agent permissions (read/write)

```
You: "Show me all EC2 instances that don't have the 'environment' tag"

Skyflo: "I found 14 EC2 instances missing the 'environment' tag. Here they are:
[table of instances]

Would you like me to add this tag to these instances?"
```

## 📦 Repositories

| Repository | Purpose | License |
|---|---|---|
| [skyflo](https://github.com/skyflo-ai/skyflo) | Main entry point | Apache 2.0 |
| [skyflo-engine](https://github.com/skyflo-ai/engine) | Core intelligence | BUSL 1.1 |
| [skyflo-api](https://github.com/skyflo-ai/api) | Backend server | BUSL 1.1 |
| [skyflo-frontend](https://github.com/skyflo-ai/frontend) | User interface | Apache 2.0 |
| [skyflo-kubernetes-agent](https://github.com/skyflo-ai/kubernetes-agent) | Kubernetes agent | Apache 2.0 |
| [skyflo-aws-agent](https://github.com/skyflo-ai/aws-agent) | AWS agent | Apache 2.0 |

## 🎯 For Who?

Skyflo.ai is designed for:

- **DevOps Engineers**: Streamline infrastructure management
- **Cloud Architects**: Design and optimize cloud environments
- **IT Managers**: Maintain oversight and control costs
- **SRE Teams**: Ensure reliability and performance
- **Security Professionals**: Enforce security policies and compliance

## 🤝 Contributing

We welcome contributions to Skyflo.ai! Whether you're fixing bugs, improving documentation, or proposing new features, your contributions are welcome.

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'feat: add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Submit** a pull request

Please follow our [contributing guidelines](https://github.com/skyflo-ai/skyflo/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/skyflo-ai/skyflo/blob/main/CODE_OF_CONDUCT.md).

## 🌐 Community

- Join our [Discord](https://discord.com/invite/kCFNavMund) server
- Follow us on [X](https://x.com/skyflo_ai)
- Subscribe to our [YouTube](https://www.youtube.com/@skyfloai) channel
- Read our [blog](https://skyflo.ai/blog) for the latest updates

## 📚 Resources

- [Website](https://skyflo.ai)
- [Documentation](https://skyflo.ai/docs)
- [Getting Started Guide](https://skyflo.ai/docs/getting-started)
- [API Reference](https://skyflo.ai/docs/api)
- [Release Notes](https://skyflo.ai/docs/releases)

## 📄 License

Skyflo.ai has different licensing based on repositories:
- Open-source components are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- Proprietary components use the [Business Source License 1.1](https://mariadb.com/bsl11/)

See the LICENSE file in each repository for specific details.

---

<p align="center">
  <sub>Built with ❤️ by the Skyflo.ai team</sub>
</p>
