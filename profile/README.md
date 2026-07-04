<div align="center">

<img src="https://raw.githubusercontent.com/orchestratagents/.github/main/profile/assets/banner.png" alt="Orchestrator — Agent Runtime Platform" width="100%">

### Create, govern, and deploy AI agents — without the framework.

A managed agent **runtime** and **control plane** for businesses: the power of agent frameworks,
packaged behind a guided dashboard, tenant isolation, sandboxed execution, policy controls,
usage tracking, and production deployment surfaces.

</div>

---

## What is Orchestrator?

Companies want AI agents in their product, website, and support flows — but building them means
wrestling with agent frameworks, execution schemas, sandbox orchestration, streaming protocols,
model routing, and infrastructure.

**Orchestrator removes that.** A business creates an agent from a guided UI, attaches
business-facing skills, picks a runtime profile, tests it in a playground, and deploys it — via
API, a hosted chat page, an embed snippet, or a WordPress plugin. Everything runs on a secure,
observable, multi-tenant runtime.

## Capabilities

| | |
| --- | --- |
| 🧩 **Guided agent builder** | Define model, instructions, skills, policies, and runtime profile — no framework code. |
| 🛡️ **Sandboxed runtime** | Each agent runs in an isolated container profile with CPU/memory, filesystem, and network rules. |
| 🏢 **Multi-tenant by design** | Data, API keys, sessions, usage, and policies are scoped per company. |
| 🔍 **Observable & governed** | Live sessions, traces, approvals, usage, cost, and tier limits — every action is auditable. |
| 🚀 **Deploy anywhere** | REST API + SDKs, JS embed widget, hosted chat page, custom subdomain, or WordPress plugin. |
| ⚙️ **Policy & approvals** | Control which actions need approval, which models and profiles are allowed, and how usage is enforced. |

<div align="center">
  <img src="https://raw.githubusercontent.com/orchestratagents/.github/main/profile/assets/dashboard.png" alt="Orchestrator admin dashboard — live telemetry, sessions, traces, and agents" width="88%">
</div>

## How it works

```text
Customer / Operator UI  →  Frontend / Admin Panel  →  Platform API  →  Agent Brain Runtime
                                                                          ├─ LLM provider
                                                                          ├─ Capability registry
                                                                          ├─ Docker sandbox
                                                                          ├─ Secrets / storage
                                                                          ├─ Postgres
                                                                          └─ SSE event stream
```

The runtime creates sessions, builds instruction and policy context, calls the model, executes
approved actions, streams events, writes traces, enforces limits, and stores durable state.

## Deploy an agent, your way

- **API + SDKs** — full control from your own product.
- **Embed widget** — a small JavaScript snippet on any site.
- **Hosted chat page** — a branded URL (or your own subdomain) with no frontend work.
- **WordPress plugin** — connect, pick an agent, and place it with a block or shortcode.

## Built with

TypeScript · Next.js · Express · PostgreSQL (Drizzle) · Docker · Turbo · Server-Sent Events

<div align="center">
<sub><b>Orchestrator</b> · Agent Runtime Platform</sub>
</div>
