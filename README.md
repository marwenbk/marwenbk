<p align="center">
  <img src="./assets/command-center.svg" alt="Marwen Ben Khemis - operational systems engineer" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/marwenbk/engineering-field-notes"><img src="https://img.shields.io/badge/Field_Notes-111827?style=for-the-badge&logo=github&logoColor=white" alt="Engineering field notes" /></a>
  <a href="https://www.linkedin.com/in/marwen-ben-khemis-113809118"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://medium.com/@marwanbk2000"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:marwanbk2000@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## What I Build

I build operational software where messy real-world workflows become typed, observable, reliable systems.

<table>
<tr>
<td width="50%" valign="top">

### Bounded AI Systems

Model extraction where ambiguity exists. Deterministic authority where business truth matters.

`OCR` `typed snapshots` `human review` `event gates` `deterministic parsing`

</td>
<td width="50%" valign="top">

### Role-Centered UX

Interfaces designed around responsibility, risk, permissions, timing, and next action.

`operator consoles` `admin workspaces` `workflow state` `error prevention`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Offline And Edge Retail

Checkout flows, local queues, stale-auth handling, receipt printers, scanners, and scale integrations.

`Flutter` `local state` `sync loops` `ESC/POS` `hardware protocols`

</td>
<td width="50%" valign="top">

### Reliability And Delivery

Systems that expose degraded state, recover in background loops, and encode domain failures in CI.

`event logs` `freshness` `workers` `GitHub Actions` `PM2` `Ansible`

</td>
</tr>
</table>

## Public Proof

[**engineering-field-notes**](https://github.com/marwenbk/engineering-field-notes) is where I turn private production lessons into public-safe engineering notes.

Current notes cover:

- **The model extracts; the system decides** - AI boundaries for operational systems
- **Human review is not a text box** - HITL as typed state
- **Role-centered UX** - designing big interfaces around responsibility
- **Shadow-run, then delete** - safer migration and cleanup
- **A green API ping does not mean the operation is alive** - reliability beyond `/health`
- **Offline POS is queue ownership** - resilient checkout as distributed systems work
- **The revert wave** - undoing cleanup without losing correctness

Everything there is synthetic and public-safe: no private screenshots, customer data, hostnames, credentials, raw payloads, or internal system names.

## Operating Model

```txt
document / device / user action
          |
          v
extract ambiguity -> confirm responsibility -> produce typed state
          |                    |                     |
          v                    v                     v
 deterministic rules      role-centered UI       append-only events
          |                    |                     |
          +-----------> reliable operator workflow <-+
```

## Selected Systems

| System shape | What it proves |
|---|---|
| Retail POS ecosystem | Offline-first mobile, real-time sync, generated SDKs, order/payment flows, printers, barcode, scale integration |
| AI-assisted document workflow | OCR/model extraction, human review gates, typed snapshots, event logs, background workers, operator dashboards |
| Multi-tenant business platform | WebAuthn/passkeys, TOTP, JWT auth, real-time inventory, Flutter clients, health-checked deploys |
| Engineering field notes | Public writing around architecture, reliability, product judgment, role-centered UX, and AI boundaries |

## Engineering Taste

```txt
prefer deterministic parsing when input is structured
keep model calls where ambiguity is real
make degraded state explicit
turn review into typed data
design around roles, not generic users
encode domain failures in CI
delete obsolete paths after parity is proven
```

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-111827?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-111827?style=flat&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-111827?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-111827?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Vue-111827?style=flat&logo=vue.js&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Nuxt-111827?style=flat&logo=nuxt.js&logoColor=white" alt="Nuxt" />
  <img src="https://img.shields.io/badge/Flutter-111827?style=flat&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-111827?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-111827?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Ansible-111827?style=flat&logo=ansible&logoColor=white" alt="Ansible" />
</p>

## GitHub Trace

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=marwenbk&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=34D399&text_color=CBD5E1" height="168" alt="GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=marwenbk&theme=github-dark-blue&hide_border=true&background=0D1117&ring=22D3EE&fire=F59E0B&currStreakLabel=34D399" height="168" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=marwenbk&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=CBD5E1&langs_count=8&hide=jupyter%20notebook" height="168" alt="Top languages" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/marwenbk/marwenbk/output/github-snake-dark.svg" alt="GitHub contribution trace" />
</p>
