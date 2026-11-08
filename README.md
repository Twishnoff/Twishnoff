# Tyler Wishnoff

**Founding marketer who builds the systems, not just the strategy.** I've run marketing inside early-stage B2B startups, usually as the only marketer. Now I also build the AI pipelines, product analytics and outbound tooling that take companies from zero to one and beyond.

Everything below is built with Claude in the loop: I design the systems, decide what gets built or bought, verify the output, and own every file.

## What I'm building

| Project | What it is | What the AI does |
|---|---|---|
| [Mktforge](https://github.com/Twishnoff/Mktforge) · [live app](https://app.mktforge.io) | A free marketing platform for founders and first marketing hires: nine agentic tools that draft positioning, personas, messaging, battle cards, and more. | Each module is a Claude pipeline on Cloudflare Workers: site research, framework-driven drafting, PDF output. Bring-your-own-key billing, Slack and HubSpot integrations. |
| [GTM Engineering case study](https://twishnoff.github.io/Portfolio/GTM-Engineering) · [build tracker](https://twishnoff.github.io/GTM-Build-Tracker/) | A complete GTM engine built solo in 30 days on top of Mktforge: CI-deployed Workers, PostHog instrumentation, HubSpot as system of record, Clay enrichment and ICP scoring, an outbound campaign on real contacts, and a BigQuery/dbt data layer. Four write-ups: [instrumentation](https://www.linkedin.com/pulse/instrumenting-plg-funnel-from-scratch-tyler-wishnoff-gaihc/), [HubSpot as system of record](https://www.linkedin.com/pulse/hubspot-system-record-logic-tyler-wishnoff-b7zfc/), [the outbound loop](https://www.linkedin.com/pulse/you-wont-use-tool-built-why-should-i-tyler-wishnoff-hbbcc/), [the data layer](https://www.linkedin.com/pulse/gtm-data-layer-team-one-tyler-wishnoff-4sxrc/). | Instrumented end to end: every signup, run and PDF is an event, the activation funnel is live, and replies are classified by Claude and handed off to Slack. |
| [Battle Card Generator](KEEP) | One-page competitive battle cards for a named competitor and ICP, delivered as PDF. | Multi-step research and drafting pipeline with a no-search scoring pass as a quality gate. |
| [Customer Intelligence](KEEP) | A dashboard that maps a company's products to the job titles most likely to buy, plus competitors to watch. | Website analysis → ICP inference → structured output a PMM can act on. |
| [Minglish](KEEP) | Professional-English practice for native Mandarin speakers. | Analyzes word pronunciation and generates practice words based on user performance. |

## How I work

- **Craft with empathy.** Everything I build starts with asking "who is this for, and what am I trying to help them accomplish?" Nothing gets built without a plan and goal.
- **Build for production.** Mktforge has real users; the case study reports real activation and reply rates, including the misses.
- **Buy, build or skip, within budget.** I develop scalable systems that care about revenue. I'm always working to bring down the cost of anything I build without sacrificing usability or security.
- **Contracts over conventions.** The analytics event taxonomy is documented and CI-enforced: events that aren't in the contract fail the build.

## Stack

HubSpot API & workflows · Clay · Apollo · Zapier · Slack apps · PostHog · BigQuery · dbt · Looker Studio · Cloudflare Workers, Queues & KV · GitHub Actions · Claude API · Firebase

## Elsewhere

[Portfolio](https://twishnoff.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/wishnoff) · [mktforge.io](https://mktforge.io)
