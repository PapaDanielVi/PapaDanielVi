<div align="center">

# Hi, I'm PapaDanielVi 👋
### Senior Back-End & Distributed Systems Engineer · Go & Cloud Infrastructure

*"Code is a liability, not an asset."*

[![GitHub Followers](https://img.shields.io/github/followers/PapaDanielVi?label=Followers&style=flat-square&color=2563eb)](https://github.com/PapaDanielVi?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/PapaDanielVi?label=Total%20Stars&style=flat-square&color=f59e0b)](https://github.com/PapaDanielVi?tab=repositories)
[![Homebrew Tap](https://img.shields.io/badge/Homebrew-Tap%20Available-orange?style=flat-square&logo=homebrew)](https://github.com/PapaDanielVi/homebrew-tap)
[![Dev.to](https://img.shields.io/badge/Dev.to-Technical%20Articles-black?style=flat-square&logo=devdotto)](https://dev.to/papadanielvi)
[![Medium](https://img.shields.io/badge/Medium-Blog-black?style=flat-square&logo=medium)](https://medium.com/@PapaDanielVi)

---

</div>

## 🧭 Engineering Focus

I design and build resilient distributed systems, cloud-native SDKs, and developer infrastructure tooling in **Go** and **Python**. My work centers on high-performance back-ends, zero-polling runtime synchronization, multi-tenant isolation, telemetry-driven observability, and client-side cryptographic security.

- **Distributed Primitives & SDKs**: Building low-overhead Go SDKs for transparent tenant context propagation and real-time configuration streaming without polling loops.
- **Infrastructure & Observability**: Production-grade Prometheus exporters (including Bolt-protocol instrumentation for graph databases), Kubernetes/OpenShift workloads, and GitOps pipelines.
- **Security & Developer Tooling**: Zero-knowledge Git-backed secret managers, cross-platform secret migration pipelines, and developer productivity CLIs distributed via Homebrew.
- **Agentic AI & Edge Systems**: Architecting autonomous agents on ARM64 hardware (Raspberry Pi), headless browser search engines without third-party APIs, and context engineering patterns for AI workflows.

---

## ⚡ Featured Open-Source Projects

### 🏛️ Distributed Systems & Cloud-Native SDKs

| Project                                                | Description                             | Architecture / Key Highlights                                                                                                                                            | Stack                                    |
| :----------------------------------------------------- | :-------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------- |
| **[apadana](https://github.com/PapaDanielVi/apadana)** | Multi-Tenant SaaS SDK for Go            | Transparent tenant context propagation across HTTP & gRPC, tenant-scoped rate limiting, per-tenant Prometheus metrics, and automated tenant data isolation.              | `Go` `gRPC` `OpenTelemetry` `Prometheus` |
| **[poya](https://github.com/PapaDanielVi/poya)**       | Zero-Polling Dynamic Runtime Config SDK | Real-time configuration synchronization using type-safe generics (`DcValue[T]`). Watches etcd, HashiCorp Vault, Redis, MySQL, and PostgreSQL with zero polling overhead. | `Go` `etcd` `Vault` `Redis` `PostgreSQL` |

### 🛡️ Security, DevOps & Observability Tooling

| Project                                                              | Description                                   | Architecture / Key Highlights                                                                                                                                                             | Stack                                  |
| :------------------------------------------------------------------- | :-------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------- |
| **[ostrakon](https://github.com/PapaDanielVi/ostrakon)**             | Zero-Knowledge Git-Backed Secret Manager      | Client-side encrypted CLI secret manager targeting private GitHub/GitLab repositories. Built with Argon2id key derivation and AES-256-GCM authenticated encryption.                       | `Go` `Argon2id` `AES-GCM` `CLI`        |
| **[neo4j-exporter](https://github.com/PapaDanielVi/neo4j-exporter)** | Prometheus Bolt-Protocol Exporter for Neo4j   | High-performance metrics exporter for Neo4j graph databases. Queries JVM internals, page cache, Bolt connection pools, and custom Cypher probes via Bolt; supports K8s service discovery. | `Go` `Prometheus` `Neo4j` `Kubernetes` |
| **[secret-shift](https://github.com/PapaDanielVi/secret-shift)**     | Cross-Provider Secrets & Config Migration CLI | Bi-directional CLI migration pipeline syncing secrets and environment variables across GitHub, GitLab, Kubernetes Secrets/ConfigMaps, HashiCorp Vault, and etcd.                          | `Go` `Kubernetes` `Vault` `etcd`       |

### 🤖 Agentic AI & Developer Tooling

| Project                                                                          | Description                                  | Architecture / Key Highlights                                                                                                                                                                                           | Stack                                                 |
| :------------------------------------------------------------------------------- | :------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------- |
| **[jamshid](https://github.com/PapaDanielVi/jamshid)**                           | Claude Code Multi-Profile Manager            | Terminal UI & CLI (built with Bubble Tea) for seamless project-level hot-switching between Anthropic, enterprise API keys, and OpenRouter configurations.                                                               | `Go` `Bubble Tea` `CLI` `LLM Tooling`                 |
| **[hermes-pi](https://github.com/PapaDanielVi/hermes-pi)**                       | Autonomous Edge AI Agent on Raspberry Pi     | Self-hosted 24/7 AI agent running on Raspberry Pi 5. Features Telegram voice/chat gateway, sandboxed Playwright headless Chromium for live web search (zero third-party search APIs), and Git-backed persistent memory. | `Shell` `Playwright` `Docker` `Telegram API` `SQLite` |
| **[claude-code-llm-wiki](https://github.com/PapaDanielVi/claude-code-llm-wiki)** | Agentic Workflows & Context Engineering Wiki | Living knowledge base and design patterns for Claude Code skills, context engineering, prompting architecture, and MCP (Model Context Protocol) tool integration.                                                       | `Markdown` `MCP` `Agentic AI`                         |

---

## 📦 Package Distribution

My CLI tools are packaged and distributed through an official Homebrew tap for macOS and Linux:

```bash
# Tap the repository
brew tap PapaDanielVi/homebrew-tap

# Install any CLI tool
brew install jamshid        # Claude Code multi-profile manager
brew install ostrakon       # Git-backed zero-knowledge secret manager
brew install secret-shift   # Secrets & env migration across K8s/Vault/etcd
brew install neo4j-exporter # Bolt-protocol Prometheus exporter for Neo4j
```

---

## 🛠️ Technical Competencies

- **Core Languages**: Go (primary), Python (primary), Rust, Shell / Bash
- **Distributed Systems & Cloud-Native**: Kubernetes, OpenShift, Docker, gRPC, Protocol Buffers, ArgoCD, GitOps, Linux (amd64 / arm64)
- **Data & Distributed State**: PostgreSQL, MySQL, Redis, etcd, HashiCorp Vault, Neo4j
- **Observability & SRE**: Prometheus, Grafana, OpenTelemetry, Pyroscope, Distributed Tracing
- **AI & Agentic Engineering**: Model Context Protocol (MCP), Claude Code Tooling, Headless Browser Automation (Playwright), Edge Deployments (Raspberry Pi / Ollama)

---

## ✍️ Technical Writing & Architecture Deep-Dives

- 📖 **[Secure Your Secrets the Ancient Way: Ostrakon - A Zero-Knowledge, Git-Backed CLI Secret Manager](https://dev.to/papadanielvi/secure-your-secrets-the-ancient-way-ostrakon-a-zero-knowledge-git-backed-cli-secret-manager-433n)**
  *An architectural deep-dive into client-side cryptography, Argon2id parameter tuning, and leveraging private Git repositories as auditable, zero-cost secret backends.*

---

## 🤝 For Recruiters & Engineering Leads

I specialize in **Senior / Staff Back-End**, **Distributed Systems**, and **Cloud Infrastructure / Platform Tooling** roles.

- 📍 **Location**: Istanbul, Türkiye (UTC+3) · Available for Remote worldwide
- 💼 **Domain Focus**: Distributed Back-Ends, High-Throughput Services, Cloud-Native Infrastructure & Developer Tooling
- 📧 **Direct Inquiries**: [k2527806@gmail.com](mailto:k2527806@gmail.com?subject=Engineering%20Opportunity%20-%20PapaDanielVi)
- 🐙 **GitHub**: [github.com/PapaDanielVi](https://github.com/PapaDanielVi)
- 📝 **Writing & Insights**: [Dev.to](https://dev.to/papadanielvi) · [Medium](https://medium.com/@PapaDanielVi)

<div align="center">
  <sub>Built with engineering pragmatism. Feel free to explore any of the repositories above.</sub>
</div>
