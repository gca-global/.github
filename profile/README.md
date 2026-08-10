<p align="center">
  <a href="https://sharp-matrix-teaser.lovable.app">
    <img src="https://raw.githubusercontent.com/gca-global/.github/main/brand/logo-blue.png" alt="Sharp Matrix" width="400" />
  </a>
</p>

<h3 align="center">Sharp Matrix — home under G.C.A.</h3>

<p align="center">
  Client OS for luxury real estate — powering Sotheby's affiliates outside the US across Cyprus, Hungary, Kazakhstan, and Slovenia.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat&logo=anthropic&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/RESO_DD_2.0-1A1A2E?style=flat&logoColor=white" alt="RESO" />
  <img src="https://img.shields.io/badge/OAuth_2.0_+_PKCE-EB5424?style=flat&logo=auth0&logoColor=white" alt="OAuth" />
  <img src="https://img.shields.io/badge/React_18-61DAFB?style=flat&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Deno-000000?style=flat&logo=deno&logoColor=white" alt="Deno" />
  <img src="https://img.shields.io/badge/Cursor_IDE-000000?style=flat&logo=cursor&logoColor=white" alt="Cursor" />
  <img src="https://img.shields.io/badge/Lovable-FF6B6B?style=flat&logo=heart&logoColor=white" alt="Lovable" />
  <img src="https://img.shields.io/badge/Claude-CC785C?style=flat&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white" alt="Zod" />
</p>

---

### Who is who

| Name | Role |
|---|---|
| **Sharp Matrix** | The technology platform — multi-app client OS, CDL, SSO, AI/MCP |
| **Sharp SIR** | The brokerage — Sharp Sotheby's International Realty (operations & brand) |
| **G.C.A.** | Legal and tech home for Sharp Matrix repositories ([G.C.A. GLOBAL CITIZEN ADVISORY LTD](https://github.com/gca-global)) |

This org hosts Matrix product and integration repos, including open-source MCP servers. Additional platform work also lives under [`sharpsir-group`](https://github.com/sharpsir-group).

---

### Platform Architecture

```
Channels (WhatsApp, Email, Web, Microsoft 365, Ads)
  │
  ▼
Matrix Apps ── shared App Template (React + Vite + shadcn/ui)
  │
  ├── CDL-Connected Apps ─── Pipeline, Contact Mgmt, Broker Dashboard
  │
  ├── Domain-Specific Apps ── HRMS, Financial Mgmt, ITSM
  │
  └── AI / MCP ── copilots, Xero & CRM tools, RESO-aligned agents
  │
  ▼
CDL + SSO (Supabase)  ◄──►  Databricks / MLS / Portals
```

---

### Repositories

| Project | Description |
|---|---|
| **[Qobrix CRM MCP](https://github.com/gca-global/qobrix-crm-mcp)** | Open-source read-only MCP for Qobrix CRM — RESO DD 2.0–aligned tools; **Claude.ai** and **Dust.tt** Mode D remote connectors |
| **[Qobrix CRM MCP OAuth](https://github.com/gca-global/qobrix-crm-mcp-oauth)** | Proprietary OAuth 2.1 Authorization Server companion for Modes C/D. *(private)* |
| **[Xero MCP Server](https://github.com/gca-global/sharpsir-xero-mcp-server)** | Private MCP server for Xero accounting — Matrix finance integrations. *(private)* |

**Sister open-source** (under [`sharpsir-group`](https://github.com/sharpsir-group) — not hosted here):

| Project | Description |
|---|---|
| **[MLS 2.0 Pipeline](https://github.com/sharpsir-group/mls_2_0)** | Databricks ETL + RESO Web API for MLS ingestion |
| **[Matrix Platform KB](https://github.com/sharpsir-group/matrix-platform-kb)** | Platform knowledge base — architecture, data models, processes |
| **[GitHub Watcher](https://github.com/sharpsir-group/github-watcher)** | Webhook auto-deploy for Matrix apps |

---

<p align="center">
  <strong>G.C.A.</strong> · <strong>Sharp Matrix</strong><br />
  <a href="https://sharp-matrix-teaser.lovable.app">sharp-matrix-teaser.lovable.app</a>
  ·
  <a href="https://sharpsir.group">sharpsir.group</a>
</p>
