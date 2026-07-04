<div align="center">

# ⚡ Triggo

### Automate anything, visually.

**Triggo is an AI-native workflow automation platform built for freelancers and solo automation consultants.**  
Describe what you want to automate in plain English — Triggo builds the workflow for you, instantly.

[![Status](https://img.shields.io/badge/status-building-orange?style=flat-square)](https://triggo.dev)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Made with FastAPI](https://img.shields.io/badge/backend-FastAPI-009688?style=flat-square)](https://fastapi.tiangolo.com)
[![Made with Next.js](https://img.shields.io/badge/frontend-Next.js-000000?style=flat-square)](https://nextjs.org)

[Website](https://triggo.dev) · [Report a Bug](https://github.com/yourusername/triggo/issues) · [Request a Feature](https://github.com/yourusername/triggo/issues)

</div>

---

## What is Triggo?

Most automation tools make you think like a machine — drag a node, wire a connection, configure a webhook, repeat 40 times. Triggo flips that.

You describe what you want to automate in plain English. Triggo's AI builds the workflow on the canvas for you. You review it, tweak it if needed, and run it. What used to take hours now takes minutes.

Built specifically for freelancers and solo automation consultants who deliver client workflows for a living and need a tool that works as fast as they think.

---

## Key Features

- 🤖 **AI workflow generator** — type "send me a Slack message when I get a new Gmail from a client" and watch Triggo build it on the canvas automatically
- 🎨 **Visual drag-and-drop canvas** — powered by React Flow, clean and fast
- ⚡ **First-class integrations** — Gmail, Slack, Google Sheets, Webhooks, OpenAI, and more
- 🧠 **AI node suggester** — drop a node and Triggo suggests the next logical step
- 🔍 **AI error explainer** — when a run fails, Triggo tells you why in plain language and suggests a fix
- 📊 **Run logs** — per-node status, input/output inspection, and timestamps for every execution
- 🔐 **Credential vault** — encrypted storage for all your API keys, per user
- 📦 **Workflow templates** — 10+ pre-built flows you can clone and customize in seconds

---

## Who is it for?

Triggo is built for:

- **Freelance automation consultants** who build workflows for clients and need to move fast
- **Solo developers** who want to automate their own tools without writing boilerplate
- **Small agencies** delivering automation as a service

If you've ever opened n8n or Make.com and thought "this should be faster" — Triggo is for you.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 14 + Tailwind CSS |
| Canvas | React Flow |
| Backend | FastAPI (Python) |
| Database | Supabase (PostgreSQL) |
| Auth | Supabase Auth |
| AI | OpenAI API + Google Gemini |
| Deploy (FE) | Vercel |
| Deploy (BE) | Railway |

---

## How it works

```
1. Open Triggo and describe your automation in plain English
       ↓
2. AI generates a workflow on the canvas instantly
       ↓
3. Review, tweak nodes if needed, add your credentials
       ↓
4. Hit Run — Triggo executes and logs every step
       ↓
5. Schedule it, share it, or hand it to a client
```

---

## Roadmap

### Phase 1 — Foundation
- [x] Domain registered (triggo.dev)
- [x] Brand + positioning defined
- [x] Architecture planned
- [x] GitHub repo live

### Phase 2 — Backend Core
- [ ] FastAPI project scaffold
- [ ] Workflow data model (nodes + edges)
- [ ] Execution engine (topological sort)
- [ ] 5 starter node types (HTTP, JSON transform, filter, delay, webhook)
- [ ] Supabase integration (workflow storage + run history)
- [ ] Auth (Supabase Auth)

### Phase 3 — Canvas UI
- [ ] Next.js app + Tailwind setup
- [ ] React Flow canvas integration
- [ ] Node panel (left sidebar)
- [ ] Node config drawer (right panel)
- [ ] Canvas ↔ backend wiring (save + run)

### Phase 4 — AI Layer
- [ ] AI workflow generator (describe → canvas)
- [ ] AI node suggester
- [ ] AI error explainer
- [ ] "Improve this workflow" AI audit

### Phase 5 — Integrations
- [ ] Credential vault (encrypted per user)
- [ ] Gmail node
- [ ] Slack node
- [ ] Google Sheets node
- [ ] Webhook trigger node
- [ ] OpenAI node

### Phase 6 — Launch
- [ ] Workflow templates library (10+ flows)
- [ ] Run logs UI
- [ ] Stripe billing (Free + Pro tiers)
- [ ] Production deployment
- [ ] Public beta launch

---

## Project Structure

```
triggo/
├── frontend/                  # Next.js app
│   ├── app/                   # App router pages
│   ├── components/
│   │   ├── canvas/            # React Flow canvas + nodes
│   │   ├── panels/            # Left sidebar + right config drawer
│   │   └── ui/                # Shared UI components
│   └── lib/                   # API client + utilities
│
├── backend/                   # FastAPI app
│   ├── api/                   # Route handlers
│   ├── engine/                # Workflow execution engine
│   ├── nodes/                 # Node type definitions
│   ├── models/                # Database models
│   └── main.py                # FastAPI entry point
│
└── README.md
```

---

## Getting Started (Coming Soon)

Full setup docs will be published once the MVP is complete. Star the repo to get notified.

```bash
# Clone the repo
git clone https://github.com/yourusername/triggo.git
cd triggo

# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev
```

---

## Contributing

Triggo is currently in solo development. Once the MVP is live, contributions will be welcome. Watch the repo for updates.

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**Built by [Your Name](https://linkedin.com/in/yourprofile)**  
🚧 Currently in active development · [triggo.dev](https://triggo.dev)

*If this resonates with you, drop a ⭐ — it helps more than you think.*

</div>
