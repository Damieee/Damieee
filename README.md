# Hey, I'm Dare Ezekiel 👋

**AI Engineer & Backend Engineer** · Lagos, Nigeria 🇳🇬
Building production AI for companies in 🇬🇧 the UK · 🇨🇳 China · 🇺🇸 the US · 🇦🇪 Dubai · 🇳🇬 Nigeria

I ship AI agents and backend systems that real customers pay through, every day: booking engines, payment rails, research platforms and learning tools.

> 💰 *"I don't just build systems, I build systems that make money."*

---

## 🏆 Headline

### ✈️ Viki, the AI booking agent for ValueJet Airlines: **₦300M+ in revenue**
I built and run Viki, ValueJet's AI sales agent. Customers search, book, pay for and change flights in a chat, with no human agent in the loop.

- **Every channel:** WhatsApp, Telegram, a web widget, and **voice** (speech-to-text in, voice-note replies out)
- **Full booking flow:** flight search, fare classes, passenger details, ticketing, date changes and modification payments
- **Payments:** Korapay, BudPay and Paystack, with webhooks, a payment watcher and a nightly reconciler that confirms payment against the airline ticket, so no paid booking goes unrecorded
- **Revenue ops:** an admin dashboard for conversations, tokens, channels, LLM spend and daily revenue, plus idempotent backfill tooling for missed payments
- **Cost:** moved the agent from GPT-4o to DeepSeek and cut LLM cost per token by about 90%, with per-provider cost tracking

---

## 🌍 What I'm building now

| Product | What it is | My work |
|---|---|---|
| **Viki** · ValueJet 🇳🇬 | AI airline booking and sales agent | Architecture, LLM orchestration, payments, voice, revenue dashboard |
| **Saras** · Alpharithm Investments | AI equity-research report platform | Multi-tenant FastAPI backend, LLM report generation on Refinitiv data, scheduled reports, OpenAI + OpenRouter failover. Cut report generation from 20–30 min to about 6.6 min |
| **Nuvion** · Resilience17 | Fintech payments platform | Card issuing, acquiring, payouts and payment webhooks in Node.js |
| **a·mm·a** · Appnable 🇦🇪 | Maternal-health companion app | NestJS API, own auth (email OTP, Google/Apple sign-in, ES256 JWTs), Supabase → Postgres move, Azure UAE North deployment with GitHub OIDC |
| **Look Think Do** · SeqHub | AI tutor for the AP Java exam | AI reading chat, auto-graded quizzes and tools, JupyterHub notebooks, teacher model picker, monitoring with New Relic |
| **Kokoodi** | AI product studio | Praxis.pq (AI workplace assessments), Pendroply (AI writing), AI comms platform, CV builder |
| **Gozaix** · iAurora | Mobile app | FastAPI backend and React Native app |
| **Secondary City Tech** | Tech platform | NestJS API on Neon, Upstash Redis, Cloudinary, Resend |

---

## 💡 What I do best

- 🤖 **AI agents & LLM systems:** tool-calling agents, RAG and Graph-RAG, multi-provider routing with failover, LLM grading, prompt and cost tuning
- 💳 **Payments & fintech:** gateway integrations, webhooks, reconciliation, card issuing
- 🏗️ **Backend systems:** APIs, auth, multi-tenancy, background jobs, database migrations
- ☁️ **Cloud & DevOps:** Azure, AWS, Railway, Heroku, Docker, CI/CD, monitoring

---

## 🛠️ Tech stack

```
🤖 AI/LLM     OpenAI • DeepSeek • OpenRouter • Gemini • LangChain • Neo4j • Ollama
🐍 Python     FastAPI • Flask • Celery • Pydantic • uv
🟦 Node/TS    NestJS • Express • TypeScript
🗄️ Data       PostgreSQL • Redis • MongoDB • Neon • Upstash
☁️ Cloud      Azure • AWS • Railway • Heroku • Vercel • Docker • Kubernetes
📊 Ops        New Relic • UptimeRobot • GitHub Actions
⚡ Frontend   React • Next.js • React Native • Tailwind
```

---

## 📈 Wins

**✈️ ValueJet Airlines**
- **Over ₦300M in revenue** from customers booking and managing their flights with Viki
- **About 90% lower LLM cost** per token after moving Viki from GPT-4o to DeepSeek
- **₦6.2M+ recovered** from payments that settled but were never recorded, using reconciliation and backfill tooling I built
- **Customers could change their bookings again:** fixed the bug that made the airline wrongly refuse booking changes as unpaid
- **$500K a year** saved through route-optimisation algorithms

**📊 Saras · Alpharithm Investments**
- **Reports about 4x faster:** generation went from 20–30 minutes to about 6.6
- **Kept reports running when OpenAI goes down:** calls switch over to OpenRouter automatically

**🎓 SeqHub**
- **30% less churn** during peak traffic at SeqHub AI
- **Safer deploys** on Look Think Do: a migration registry, a weekly release cycle, and New Relic + UptimeRobot monitoring

**🤰 a·mm·a · Appnable**
- **Moved the app off Supabase** to its own auth and Postgres, then deployed it to Azure UAE North

**💳 Nuvion · Resilience17**
- **Caught a supply-chain attack:** found a remote-access trojan hidden in a shared config file, which reinjected itself on every commit

---

## 📫 Let's talk

Building an AI product that needs to make money? I'd like to hear about it.

📧 joshezekiel.dev@gmail.com
