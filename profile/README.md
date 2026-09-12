<p align="center">
  <a href="https://pyahu.io">
    <img src="https://pyahu.io/logo.svg" alt="Pyahu" width="80" />
  </a>
</p>

<h3 align="center">Pyahu Platform</h3>

<p align="center">
  <strong>Great software. Built on better foundations.</strong><br />
  A development suite that brings good practices, automation and AI into your team's everyday work.<br />
  From the first project to production.
</p>

<p align="center">
  <a href="https://pyahu.io">Website</a> &middot;
  <a href="https://pyahu.io/pt">Português</a> &middot;
  <a href="https://cli.pyahu.io">CLI docs</a> &middot;
  <a href="https://pyahu.io#contact">Contact</a>
</p>

---

Welcome to **Pyahu Community** — open foundations and tools you can adopt at your own pace.

Good engineering takes more than a framework. Pyahu brings together the foundations of software
delivery, so your team spends more time on the product and less time rebuilding its development
stack. Distinct tools, one shared direction: start where your team needs help, and adopt the other
pieces as your workflow grows.

## What we believe

- **Good practices, built in** — architecture, testing and observability are part of the work from the start.
- **Automation with intent** — repeat the checks and routines; keep people in charge of the decisions.
- **A foundation you own** — open tools, versioned configuration and infrastructure you can understand.

## From idea to production

| Step | Tool | |
| --- | --- | --- |
| 01 · Prepare | [Toolchain](#pyahu-toolchain) | Get the team on the same page |
| 02 · Create | [Initializer](#pyahu-initializer--coming-soon) | Start with the right foundations |
| 03 · Develop | [AI Factory](#pyahu-ai-factory--coming-soon) | Build with AI, keep the discipline |
| 04 · Validate | [CLI](#pyahu-cli) | Make local development real |
| 05 · Operate | [Open Cluster Foundation](#pyahu-open-cluster-foundation) + [Cloud](#pyahu-cloud-enterprise) | Build infrastructure you understand |

## Community projects

| Project | What it does | Status |
| --- | --- | --- |
| [**Toolchain**](https://github.com/pyahu/toolchain) | Curated developer tools managed by mise — consistent versions on every workstation | ✅ Available |
| [**CLI**](https://github.com/pyahu/cli) | Local Kubernetes (k3d) with the services your app needs, in one command | ✅ Available |
| [**Open Cluster Foundation**](https://github.com/pyahu/open-cluster-foundation) | Production-grade Kubernetes from zero: Terraform + an observable service layer | ✅ OCI available |
| **Initializer** | Projects generated with your architecture and delivery practices already in place | 🛠️ Coming soon |
| **AI Factory** | An AI coding harness with an Extreme Programming workflow | 🛠️ Coming soon |

### Pyahu Toolchain

**Get the team on the same page.** A curated, composable set of CLI tools, organized by category
and managed with [mise](https://mise.jdx.dev). No dev container, no per-language version-manager
stack — a small cross-stack baseline plus the workflow profiles you choose: `workstation`, `java`,
`go`, `python`, `node`, `cloud`, `ai`, `arch`.

```sh
git clone https://github.com/pyahu/toolchain.git ~/.config/pyahu-toolchain
cd ~/.config/pyahu-toolchain
./install.sh workstation java cloud   # pick the profiles you use
```

→ [github.com/pyahu/toolchain](https://github.com/pyahu/toolchain)

### Pyahu CLI

**Make local development real.** Bring up a local Kubernetes cluster and the services your
application needs, then develop and validate against a reproducible stack on your machine.
PostgreSQL, ZITADEL (OIDC over local HTTPS), RabbitMQ, Valkey, Kafka, Kafka Connect + Debezium and
Kafka UI — all declared in a single `pyahu.yaml`.

```sh
curl -fsSL https://cli.pyahu.io/install.sh | sh
pyahu init --preset platform   # generate the stack
pyahu up                       # bring up the cluster
eval "$(pyahu env)"            # connect your apps
```

→ [cli.pyahu.io](https://cli.pyahu.io) · [github.com/pyahu/cli](https://github.com/pyahu/cli)

### Pyahu Open Cluster Foundation

**Build infrastructure you understand.** Production-oriented Kubernetes foundations: a Terraform
foundation per provider plus a provider-agnostic Helmfile base with Envoy Gateway, cert-manager,
CloudNativePG, Kafka, observability (Prometheus, Loki, Tempo, Grafana) and Argo CD. Every version
pinned and validated in CI. OCI/OKE today; more providers on the roadmap.

→ [github.com/pyahu/open-cluster-foundation](https://github.com/pyahu/open-cluster-foundation)

### Pyahu Initializer · coming soon

**Your next project, your team's standards.** Choose *how* to build, not just which dependencies to
install. Initializer turns architecture and organizational practices into a consistent starting
point:

- **Projects** — Spring Boot · Quarkus · Next.js
- **Structure** — monorepo or multi-repo · single frontend or microfrontends
- **Architecture & delivery** — layered or hexagonal · GitHub Actions or GitLab CI
- **Observability by design** — OpenTelemetry · Grafana · Prometheus · Loki · Tempo · GlitchTip

### Pyahu AI Factory · coming soon

**AI moves fast. Give it an engineering process.** A harness powered by Pi as the model runtime, with an Extreme Programming workflow, curated skills and specialized agents. Turn a
story into an explicit agreement, work through the test cycle and review the result — while your
team sets the boundaries. Works with hosted, local or in-house models.

```
Story → Refinement → Test first (red · green · refactor) → Implementation → Review
```

## Pyahu Cloud (Enterprise)

Community and Enterprise are complementary ways to adopt Pyahu: choose what you run yourself, and
where you want our team alongside yours.

**Pyahu Cloud** gives your code a place to run — managed delivery and operations with isolated
environments, PostgreSQL and observability. JVM-first, with guided adoption, an adoption path built
around your team and a direct relationship with the people building Pyahu.

→ [Talk to the team](https://pyahu.io#contact)

## Get involved

- ⭐ Star and watch the projects above to follow their progress.
- 🐛 Found a bug or have an idea? Open an issue in the project's repository.
- 🤝 Pull requests are welcome — source code and configuration are in your hands.
- ✉️ [hello@pyahu.io](mailto:hello@pyahu.io)

<p align="center"><sub><strong>pyahu</strong> — Better foundations. Better software.</sub></p>
