<div align="center">

<!-- Animated typing header -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=4FC3F7&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Pavlos+Vassiliou;Commercial+Head+%40+Flow+Neuroscience+%F0%9F%A7%A0)](https://git.io/typing-svg)

**Building the commercial engine for a medical device treating depression — and an AI agent to run operations.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pavlosvassiliou)
[![Flow Neuroscience](https://img.shields.io/badge/Flow_Neuroscience-4FC3F7?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMyAzYy00Ljk3IDAtOSA0LjAzLTkgOUg1LjVsNC0zLjVMNS41IDE1SDRjMCA0Ljk3IDQuMDMgOSA5IDlzOS00LjAzIDktOVM3Ljk3IDMgMTMgM3oiLz48L3N2Zz4=&logoColor=white)](https://www.flowneuroscience.com)

---

</div>

## 🧠 What I Do

I lead **commercial strategy across UK, Europe & Rest of World** at [Flow Neuroscience](https://www.flowneuroscience.com) — a Class IIa CE-marked, FDA-cleared tDCS device for treating depression. My work spans marketing, sales, ops, regulatory compliance, and scaling across three continents.

I also build AI tools to make small teams dangerously effective.

---

## 🚀 Featured Projects

### ⚡ Freud — AI Chief of Staff
> An AI agent that runs operations so I don't have to.

My personal Chief of Staff — deployed on Google Cloud, talks through Slack, thinks with Claude. Handles morning briefings, email triage, meeting prep, action tracking, and document creation. Learns from every conversation through a live context graph with weekly synthesis.

```
┌─────────────────────────────────────────────────────┐
│                   FREUD AGENT                       │
│                                                     │
│   Intelligence ──── Claude API                      │
│   Interface ─────── Slack                           │
│   Infrastructure ── Google Cloud (Firebase)         │
│   Data Layer ────── Firestore (multi-tenant)        │
│                                                     │
│   Integrations:                                     │
│   ├── Google Calendar                               │
│   ├── Gmail                                         │
│   ├── Google Drive / Docs / Sheets / Slides         │
│   └── 🔜 Amplitude · Notion · HubSpot              │
└─────────────────────────────────────────────────────┘
```

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)

---

### 🏗️ Agent Builder — Meta-Agent Framework
> An agent that builds other agents.

A separate agent that walks you through 9 knowledge buckets (role, principal, company, team, ecosystem, operating rhythm, current state, rules, marketing & brand) to configure and deploy new specialised agents. Same infrastructure, different brains.

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│  Freud (CoS) │     │  Compliance  │     │    Sales     │     │  Customer    │
│              │     │   checker    │     │   enabler    │     │    intel     │
└──────┬───────┘     └──────┬───────┘     └──────┬───────┘     └──────┬───────┘
       │                    │                    │                    │
       └────────────────────┴────────────────────┴────────────────────┘
                                    │
                        ┌───────────┴───────────┐
                        │    Agent Builder      │
                        │  9 knowledge buckets  │
                        └───────────────────────┘
```

---

### 🖥️ Command Centre — Operations Dashboard
> The first screen you see when you open your laptop.

A Next.js web dashboard that replaces Gmail as the morning view. Three-panel layout: agent/project switcher, chat interface, and live data (calendar, priorities, metrics). Reads from the same Firestore backend as Freud — one brain, multiple surfaces.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)

---

### 📚 Company Brain — Knowledge Base System
> The foundation new hires build on top of.

A 9-document knowledge architecture for Flow Neuroscience — from clinical evidence to brand guidelines. Includes a **Claims Matrix** (37 approved marketing claims with exact approved language, channel restrictions, and evidence references) and a **Comms Regulations** layer covering ASA, FDA, MDR, and platform-specific ad policies. Every AI tool at Flow reads from this brain.

```
Science ─→ Regulatory ─→ Claims Matrix ─→ Brand Guidelines ─→ Content
   │            │              │                  │               │
   └────────────┴──────────────┴──────────────────┴───────────────┘
                          Company Brain
              One update benefits every tool and person
```

---

### 🎙️ Cultura — AI-Native Creator Intelligence Platform
> Manage, monitor, and extract intelligence from creator and KOL networks in regulated industries.

A multi-tenant SaaS platform built for medical devices, pharma, and fintech — where creator relationships carry regulatory weight. Live in production with a paying client tracking ~106 creators across a multi-user workspace.

```
┌─────────────────────────────────────────────────────────────┐
│                        CULTURA                              │
│                                                             │
│   Manage ────── CRM pipeline, touchpoints, fulfilment       │
│   Listen ────── Multi-platform monitoring + AI flagging     │
│   Accumulate ── Longitudinal data banking over time         │
│   Synthesise ── LLM-powered brand narrative mapping         │
│                                                             │
│   Sources:                                                  │
│   ├── Instagram · LinkedIn · YouTube · Podcasts             │
│   ├── Academic publications                                 │
│   └── Email (SendGrid Inbound Parse)                        │
│                                                             │
│   Agent layer: MCP server with 23 tools                     │
└─────────────────────────────────────────────────────────────┘
```

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logoColor=black)

---

## 🛠️ Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Slack API](https://img.shields.io/badge/Slack_API-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## 🎯 What I'm Interested In

```typescript
const pavlos = {
    role: "Commercial Head — Flow Neuroscience",
    building: "AI agents that replace the ops hire you can't afford yet",
    interests: [
        "AI agents for operational leverage",
        "Health tech commercialisation",
        "Regulatory-compliant marketing systems",
        "Using LLMs to make small teams punch above their weight",
    ],
    currentFocus: "Agent Builder — meta-agent that deploys new agents",
    belief: "The best ops person is one you don't have to hire.",
};
```

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=pavlosvassiliou&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=4FC3F7&icon_color=4FC3F7&text_color=c9d1d9)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=pavlosvassiliou&theme=tokyonight&hide_border=true&background=0d1117&ring=4FC3F7&fire=4FC3F7&currStreakLabel=4FC3F7)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pavlosvassiliou&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=4FC3F7&text_color=c9d1d9)

</div>

---

## 🗺️ Roadmap

- [x] Deploy Freud agent on GCP with Slack interface
- [x] Google Calendar, Gmail, Drive integration
- [x] Multi-tenant Firestore context graph
- [x] 9-document Company Brain knowledge base
- [x] Claims Matrix with 37 approved claims
- [x] Live context capture + weekly synthesis
- [x] Action item tracking from natural conversation
- [x] Cultura SaaS platform live with paying client
- [ ] Agent Builder — meta-agent for deploying new agents
- [ ] Command Centre web dashboard
- [ ] Amplitude / Notion / HubSpot integrations
- [ ] Multiple output channels (Slack, email, web)
- [ ] Management UI for knowledge buckets

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=pavlosvassiliou&color=4FC3F7&style=for-the-badge&label=PROFILE+VIEWS)

*Building things that make the invisible work visible.*

</div>
