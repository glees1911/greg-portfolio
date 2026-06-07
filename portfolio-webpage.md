# Portfolio Website — Greg Lees

## Project Context
Personal portfolio for a 0-to-1 ops builder and generalist targeting BizOps/RevOps roles at Series A–B startups. Primary goal: convert visitors (hiring managers, founders) into outreach or application actions.

Deployed via GitHub → Vercel.

---

## Core Message
Greg Lees builds operating infrastructure from scratch in resource-constrained environments. He has done it across defense tech, minor league baseball, and manufacturing/engineering. He is not a specialist — he is the person you hire when nothing exists yet.

---

## Site Sections

### Hero
- Name: Greg Lees
- Headline: I design operations for growing teams.
- Subline: From zero to functional — without pulling your team off mission.
- CTA buttons: Resume (PDF download) and LinkedIn (external link)
- Tone: direct, confident — no vague buzzwords

### Why Your Team Needs a Generalist
Use this copy verbatim:

---

**Most early-stage teams don't have an operations problem. They have a "no one owns this" problem.**

The CRM isn't set up. Onboarding is a Slack thread. The hiring process lives in someone's head. Every team is executing, but nothing connects.

That's where I come in.

I build the operating layer that growing teams skip when they're moving fast — the systems, workflows, and infrastructure that turn a capable team into a functional organization. Not as a specialist in one function, but as someone who sees how the pieces fit and builds accordingly.

Specialists deepen expertise. Generalists create the connective tissue between it.

If your team is past the chaos-is-fine stage but doesn't have the infrastructure to match your ambition, let's talk.

---

### How I Operate
Use this copy verbatim:

---

I don't wait for a playbook. When I join a team, I orient fast, find what's broken or missing, and start building — while keeping the people who have to live in these systems at the center of every decision.

- **Clarity First |** Define success before building solutions.
- **Simplify Relentlessly |** Great systems reduce effort, not add to it.
- **Design for Adoption |** Tools only work when people actually use them.
- **Bias for Momentum |** Progress beats perfection.
- **Built to Evolve |** Systems should scale with the team, not constrain it.

---

### Expertise
Use this copy verbatim:

---

**Systems that Scale**
I design connected operating systems that give growing teams a foundation to build on.

**Process Design & Optimization**
I streamline how work gets done, eliminating friction and turning complex workflows into simple, repeatable processes.

**People & Team Enablement**
I build systems people actually use — because adoption is the only metric that matters.

**Strategy Into Execution**
I turn strategy into execution by aligning people, processes, and priorities around what matters most.

---

### Tools & Certifications
Use this structure verbatim. Display as grouped categories, not a flat list.

---

**Workspace**
- Notion *(Notion Essentials, Workflows, and Advanced certifications)*
- Airtable
- Google Workspace
- Monday.com

**Automation**
- Make *(Make Foundation certification)*
- HubSpot *(Marketing Hub, Sales Hub, and Revenue Operations certifications)*

**AI**
- Claude
- ChatGPT

**Other**
- Slack
- Canva
- Miro

---

### Projects & Case Studies
Display as cards. Use the context/what I built/outcome structure for each. Do not invent details.

---

**Card 1 — AI-Assisted HubSpot Landing Page**
Category: AI, MarOps

Context: HubSpot's native landing page builder has real design limitations. Most teams work around it or settle.

What I built:
- Designed the page in Claude Design using prompts and manual iteration
- Handed off to Claude Code to extend and finalize the build
- Generated production-ready HTML, published directly in HubSpot via Design Manager using HTML + HubL

Outcome: A fully custom landing page hosted in HubSpot — without a developer, without a third-party page builder, and without compromising on design.

Tags: Claude, HubSpot, AI, MarOps

---

**Card 2 — GTM Operations Infrastructure**
Category: RevOps, MarOps

Context: LJB had no marketing operations infrastructure. Lead management was manual, reporting didn't exist, and the GTM team had no operational foundation to work from.

What I built:
- Stood up lead management, automated workflows, and real-time reporting in HubSpot in under 30 days
- Architected end-to-end contact management, lifecycle stages, MQL criteria, routing logic, and segmentation for a 14-person GTM team
- Built a Monday.com operations system with live dashboards and automations, eliminating manual tracking department-wide

Outcome: A fully systematized GTM function built from zero — giving a 14-person team the operational foundation to execute without the administrative overhead.

Tags: HubSpot, Monday.com, RevOps, MarOps, Process Design

---

**Card 3 — Sponsorship Operations at the Dayton Dragons**
Category: BizOps, Process Design

Context: The partnerships function had no operational infrastructure — sponsor management was fragmented, workflows were informal, and nothing was centralized.

What I built:
- Created the systems, workflows, and delivery engine that turned fragmented sponsor management into a central function from scratch
- Designed and managed operational infrastructure supporting $3.3M+ in annual sponsorship revenue
- Built activation workflows, partner communications, and cross-functional execution across 60+ accounts

Outcome: A partnerships operation built from nothing that became the operational backbone for one of Minor League Baseball's best-attended franchises.

Tags: Operations, Process Design, Revenue Operations

---

### Testimonials
Use this copy verbatim. Two testimonials only — do not add more without confirmation.

---

> "I've had the pleasure of working with Greg for more than 6 years. He's a huge asset to our team in many ways. Greg is hardworking, dedicated, trustworthy, smart, honest, and detail oriented. He's incredibly humble and has a passion to serve others. The work he has done at the Dragons and for his corporate partners never goes unnoticed; he advocates for what he believes in and I admire that. I can't say enough about Greg! He's simply awesome."

**Brandy G.** | Executive Vice President & Assistant GM, Dayton Dragons Baseball Club

---

> "Greg is excellent at making progress and solving problems, even in uncertain situations and with unclear direction. He regularly comes to the table with new ideas or solutions. He has been an excellent and supportive teammate with a 'can-do' attitude, always looking to make something better at the end of the day."

**Stacie H.** | COO, Mile Two

---

### Contact / CTA
- Simple: email link or contact form
- Optional: link to Resume and LinkedIn again

---

## Design Constraints

- Mobile-first, responsive
- Fast load — no heavy frameworks unless already committed to one
- Accessible (semantic HTML, sufficient color contrast, alt text)
- No stock photos of offices or hands shaking
- Prefer one strong typographic hierarchy over decorative complexity
- Avoid: purple gradients, generic SaaS aesthetics, hero animations that delay content

---

## Content & Copy Rules

- Write in first person, active voice
- Specific > general. "Built a HubSpot marketing pipeline from scratch in 30 days" > "Improved marketing operations"
- No jargon that doesn't mean anything: "leverage," "synergy," "passionate about"
- Every section should answer: *so what?* — if it doesn't, cut it

---

## File & Code Conventions

- Use semantic HTML elements (nav, main, section, article, footer)
- CSS: custom properties for colors, fonts, spacing — no magic numbers
- JS: vanilla unless a framework is already in use; no jQuery
- Images: use descriptive alt text; optimize before committing
- No unused dependencies

---

## What to Avoid

- Do not invent experience, outcomes, or quotes
- Do not add sections not listed above without confirming first
- Do not use placeholder lorem ipsum in final builds — use realistic placeholder content
- Do not over-engineer — this is a portfolio, not a SaaS product
