<div align="center">

# Sabrina Heydel

### AI Product Builder · Full-Stack Digital Systems

**I turn complex business processes into simple, connected and measurable digital products.**

From product discovery and UX to data, APIs, automation, QA, analytics and deployment.

[![Product Resume](https://img.shields.io/badge/Product%20Resume-Open-1B1B2F?style=for-the-badge&logo=readme&logoColor=white)](https://product-craft-suite-68.lovable.app/en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sabrina-heydel-86021a23b/)
[![Agence 360 Digital](https://img.shields.io/badge/Agence%20360%20Digital-Website-D4AF37?style=for-the-badge&logo=googlechrome&logoColor=1B1B2F)](https://www.agence360digital.fr/)

</div>

---

## What I build

| Focus | Examples | Outcome |
|---|---|---|
| **AI Products** | Copilots, intelligent interfaces, AI-ready workflows | Faster decisions and better user experiences |
| **Digital Systems** | CRM, dashboards, portals, internal tools | One clear operational layer |
| **Automation** | APIs, workflows, data flows, connected actions | Less repetitive work and fewer handoffs |
| **Client & Learning Experiences** | Booking, training spaces, client portals | More structured delivery and follow-up |
| **Product Strategy** | Discovery, UX, architecture, delivery | Technology aligned with real business needs |

> **Every project starts with a business problem.**  
> Not with a technology.

`Business problem → Product discovery → UX → Architecture → Build → Automate → Measure`

---

## Selected work

### 01 · TalentFlow AI

**AI-assisted recruitment workspace** designed to turn fragmented recruiting workflows into one clear decision environment.

**Problem**  
Recruitment teams often manage candidate information, interviews, feedback and follow-up across disconnected tools, creating context switching and poor visibility on priorities.

**Product**  
A bilingual recruitment workspace combining pipeline visibility, candidate decision support, interview coordination, guided demo flows, feedback and product analytics.

**Expected value**  
Hypothesis to validate with early adopters: **2–4 h saved per recruiter per week** on candidate preparation, interview coordination and feedback consolidation. Measured through prep time and guided-demo completion in PostHog.

**My role**  
Product discovery · Workflow analysis · UX/UI · Front-end architecture · AI-assisted development · QA · Analytics instrumentation · Deployment

**Core stack**  
Next.js · React · TypeScript · PostHog EU · Webflow Cloud · GitHub Actions

[![Live Demo](https://img.shields.io/badge/Open-Live%20Demo-005CC5?style=flat-square)](https://talentflow-ai-dash.webflow.io/)
[![Repository](https://img.shields.io/badge/View-Repository-1B1B2F?style=flat-square&logo=github&logoColor=white)](https://github.com/Sabrinaheydel/demo-talentflow-ai)

> Portfolio demo using simulated data and AI-ready product architecture. No real candidate data is processed.

### 02 · Real Estate Platform & CRM

**Full-stack acquisition and CRM product demo** showing how a public website can feed an operational sales workflow instead of stopping at isolated forms.

**Problem**  
Real-estate teams receive demand through listings, calculators, valuation requests and candidate profiles, but those signals are often fragmented and require manual qualification.

**Product**  
A connected system where website interactions can become structured CRM leads with scoring, next actions, appointments, property matching and a secure public demo sandbox.

**Expected value**  
Hypothesis to validate with a pilot agency: **3–5 h saved per agent per week** on manual lead qualification and follow-up planning, plus a faster first response to new leads.

**My role**  
Business analysis · Product discovery · UX · System design · Data modelling · Supabase/RLS · Server authorization · Automation logic · QA · Demo architecture · Deployment

**Core stack**  
React · TanStack · TypeScript · Supabase · PostgreSQL · RLS · APIs · Brevo · GA4 · GitHub

[![Guided Demo](https://img.shields.io/badge/Test-Guided%20CRM%20Demo-D4AF37?style=flat-square)](https://reims-gem-real-estate.lovable.app/demo)
[![Repository](https://img.shields.io/badge/View-Repository-1B1B2F?style=flat-square&logo=github&logoColor=white)](https://github.com/Sabrinaheydel/demo-real-estate-reims-prestige)

> Public beta using fictional data, isolated demo roles and simulated sensitive actions.

### 03 · Product Resume

**Bilingual interactive resume built as a small web product**, with responsive UX and recruiter-friendly PDF delivery.

**Product**  
FR/EN web resume, mobile-safe PDF export with clickable links, print-quality Chromium PDFs generated automatically in GitHub Actions and structured case studies for product work.

**Value delivered**  
One content update refreshes the web resume and both PDFs: no manual export, no out-of-sync versions.

**My role**  
Product positioning · Information architecture · UX · React/TypeScript implementation · PDF workflow · QA · GitHub automation

**Core stack**  
React · TypeScript · TanStack Start · jsPDF · html2canvas-pro · Playwright/Chromium · GitHub Actions

[![Live Resume](https://img.shields.io/badge/Open-Live%20Resume-005CC5?style=flat-square)](https://product-craft-suite-68.lovable.app/en)
[![Repository](https://img.shields.io/badge/View-Repository-1B1B2F?style=flat-square&logo=github&logoColor=white)](https://github.com/Sabrinaheydel/Sabrina-product-resume)

### 04 · PSPO Coach

**Grounded AI learning coach** built to prepare the Professional Scrum Product Owner I (PSPO I) certification, as a personal study tool.

**Problem**  
Certification prep is usually passive: reading a guide, then taking random practice tests. Learners forget, repeat the same mistakes, and generic AI chatbots can confidently invent rules that are not in the official source.

**Product**  
A bilingual (FR/EN) learning app in which every answer is traceable to the official Scrum Guide 2020:

- **Daily challenge** (about 5 minutes): one animated capsule, three questions targeted at weak spots and one key term, with a day streak
- **6 animated, narrated capsules** and **3 interactive diagrams** (Scrum Team, artifacts and commitments, events timeline)
- **133 questions**: Scrum Guide rules, real-life scenarios and value measurement (Evidence-Based Management), with spaced repetition on mistakes
- **Timed mock exam** (80 questions, 60 minutes, 85% pass mark), **mistake log** and **weekly report**
- **47-term glossary**, a drag-and-drop sorting game and a 2-minute true/false game
- **"Explain it to a sales rep"** mode: the learner explains a concept in their own words (typed or dictated) and the AI scores it against the guide
- **"Ask the guide"**: answers only from the Scrum Guide, with exact quotes, and says *"I don't know"* when the answer is not in the source

**Expected value**  
Target: pass PSPO I (85% or more) after six weeks at one hour a day, with progress, weak topics and a pass-probability estimate tracked in the app. The same mechanics (daily challenge, grounded answers, weekly report) can keep training participants active for weeks after a session.

**How it is built**  
- One self-contained web page (HTML, CSS, vanilla JavaScript), published as a Claude artifact. No framework, no external backend to maintain.
- A Python build script generates the question bank as JSON and **checks that every quote exists word for word in the Scrum Guide** before publishing.
- Animations and diagrams are hand-built SVG, with keyboard access, light and dark themes and reduced-motion support.
- AI features call Claude with the relevant guide sections as the only context (retrieval-grounded prompting). Every quote the model returns is **verified in the browser against the source text**; unverified quotes are never shown.
- Progress is stored privately per user; speech uses text-to-speech and dictation, with a text-only fallback.

**My role**  
Product discovery · Learning design · UX/UI · Content architecture · Prompt and guardrail design · Front-end development · QA

**Core stack**  
HTML · CSS · JavaScript · SVG · Python · JSON · Claude (Anthropic) · Playwright (QA)

<p>
  <img src="assets/pspo-coach/capsule.png" alt="Animated capsule: the Sprint cycle" width="32%" />
  <img src="assets/pspo-coach/scenario.png" alt="Scenario question with its source quote" width="32%" />
  <img src="assets/pspo-coach/vocabulary.png" alt="Glossary card: Definition of Done" width="32%" />
</p>

> Private personal tool. Content based on the Scrum Guide 2020 by Ken Schwaber and Jeff Sutherland and the Evidence-Based Management Guide by Scrum.org, both licensed CC BY-SA 4.0.

---

## Core stack

**Product & design**  
<img height="20" src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" /> <img height="20" src="https://img.shields.io/badge/Lovable-FF4A64?style=flat-square" alt="Lovable" /> <img height="20" src="https://img.shields.io/badge/Webflow-146EF5?style=flat-square&logo=webflow&logoColor=white" alt="Webflow" />

**Development & data**  
<img height="20" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" /> <img height="20" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" /> <img height="20" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000000" alt="React" /> <img height="20" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" /> <img height="20" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img height="20" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />

**AI & automation**  
<img height="20" src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" /> <img height="20" src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" /> <img height="20" src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" /> <img height="20" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n" /> <img height="20" src="https://img.shields.io/badge/Make-6D00CC?style=flat-square" alt="Make" />

**Deployment & quality**  
<img height="20" src="https://img.shields.io/badge/Webflow%20Cloud-146EF5?style=flat-square&logo=webflow&logoColor=white" alt="Webflow Cloud" /> <img height="20" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" /> <img height="20" src="https://img.shields.io/badge/PostHog-000000?style=flat-square&logo=posthog&logoColor=white" alt="PostHog" /> <img height="20" src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" />

**Growth & operations**  
<img height="20" src="https://img.shields.io/badge/Brevo-0B996E?style=flat-square&logo=brevo&logoColor=white" alt="Brevo" /> <img height="20" src="https://img.shields.io/badge/Google%20Analytics-E37400?style=flat-square&logo=googleanalytics&logoColor=white" alt="Google Analytics" /> <img height="20" src="https://img.shields.io/badge/Search%20Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white" alt="Google Search Console" />

<sub><strong>Also working with:</strong> JavaScript · REST APIs · JSON · Webhooks · Framer · Bubble.io · Canva · Perplexity · Mailchimp · Apollo.io · AnswerThePublic · Notion · Stripe · Cal.com · Whop · OVHcloud</sub>

### 05 · A360 OS & Radar 360

**My own AI operating system, used daily to run my consulting activity.** A360 OS is the cockpit (priorities, tasks, knowledge, tools, validations). Radar 360 is its AI prospecting engine.

**Problem**  
As a solo consultant, prospecting, project framing and market watch were eating most of my week, at the expense of client delivery.

**Product**  
- **Radar 360** prepares about **20 qualified prospects every night**: research, verified contact and a draft message. I review them in **about 5 minutes each morning**; nothing is sent without my approval.
- **A360 OS** brings priorities, tasks, knowledge and actions into one cockpit, with a sourced AI copilot and a validation center for sensitive actions.
- **Weekly AI and market watch**: topic briefs indexed in the copilot's memory and reused when framing client projects.

**Results**  
- **About 15 h saved per week from the first week**, then **about twice as much (≈30 h/week)** once prospecting, project framing and AI/market watch were automated *(self-measured estimate)*.
- **Controlled AI costs**: monthly budgets capped at **€8 for Radar 360** and **€4 for A360 OS**, using the lightest model suitable for each task.

**What I learned**  
An early recommendation did not fit a prospect's business. It revealed a qualification problem, which I fixed by separating facts from hypotheses, showing sources on every insight and requiring validation before any message goes out.

**My role**  
Product owner and builder: discovery, architecture, data model, prompts and guardrails, automation, QA, monitoring.

**Core stack**  
React · TypeScript · TanStack Start · Supabase (PostgreSQL, EU region) · LLM APIs · Sentry · PostHog · Lovable · Claude Code

> Private tools used in production for my own activity. No public demo; walkthrough available on request.

---

## Use case framing template

The grid I use before building anything, here filled in for the PSPO Coach.

| Step | Question | PSPO Coach |
|---|---|---|
| **Business need** | What problem, for whom, how often? | Certification prep is passive and generic AI tools invent rules. |
| **Target users** | Who uses it, who decides? | One learner, studying one hour a day. |
| **Data access** | Which sources, which permissions? | Scrum Guide 2020 and EBM Guide (CC BY-SA 4.0), private progress per user. |
| **Size** | What is the smallest useful version? | Question bank + mock exam first; capsules, games and prediction next. |
| **Value** | What is the quantified expected gain? | Pass PSPO I (85% or more) in six weeks at one hour a day. |
| **Success metrics** | How will we know? | Mock-exam scores, weak topics, daily streak, pass-probability estimate. |
| **Guardrails** | What must never happen? | No answer without a verified quote; "I don't know" outside the source. |
| **Hand-off** | What does the team need to run it? | README, build script that checks every quote, QA scripts. |

---

## How I work

**01. Diagnose** · understand the workflow, friction and business objective  
**02. Design** · define the product, UX and information architecture  
**03. Architect** · choose the appropriate stack, data model, permissions and integrations  
**04. Build** · prototype fast with Claude Code and Lovable, then harden the logic and connected workflows  
**05. Ship & measure** · QA, deploy, instrument usage and create a feedback loop  
**06. Hand off** · document decisions, architecture and release gates so another team can run and scale it

---

## Let's build something useful

### Have a business process that should work better? Let's talk.

I work with businesses, agencies and product teams on digital products, AI-assisted tools, internal systems, automation and client experiences.

<div align="center">

[![Website](https://img.shields.io/badge/Website-agence360digital.fr-1B1B2F?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.agence360digital.fr/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sabrina%20Heydel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sabrina-heydel-86021a23b/)

</div>
