# Tyler Wishnoff

**Marketing leader who builds the systems, not just the strategy.** I've run marketing inside early-stage B2B startups, usually as the only marketer. Now I build the AI pipelines, product analytics and outbound tooling that take companies from zero to one and beyond.

Everything below is built with Claude in the loop: I design the systems, decide what gets built or bought, verify the output, and own every file. 

## What I'm building

| Project | What it is | What the AI does |
|---|---|---|
| [**Mktforge**](https://github.com/Twishnoff/Mktforge) · [live app](https://app.mktforge.io) | A free marketing platform for founders and first marketing hires: nine agentic tools that draft positioning, personas, messaging, battle cards, and more. | Each module is a Claude pipeline on Cloudflare Workers: site research, framework-driven drafting, PDF output. Bring-your-own-key billing, Slack and HubSpot integrations. |
| [**GTM Build Log**](https://twishnoff.github.io/GTM-Build-Tracker/) | A 30-day public build of the GTM engineering stack on top of Mktforge: CI-deployed Workers, PostHog instrumentation, HubSpot as system of record, Clay enrichment, an outbound campaign on real contacts, and a BigQuery/dbt data layer. Updated daily. | Instrumented end-to-end — every signup, run and PDF is an event; the activation funnel is live. Weekly write-ups with real numbers. |
| [**Battle Card Generator**](https://github.com/Twishnoff/Battlecard-Generator) | One-page competitive battle cards for a named competitor and ICP, delivered as PDF. | Multi-step research and drafting pipeline with a no-search scoring pass as a quality gate. |
| [**Customer Intelligence**](https://github.com/Twishnoff/Customer-Intelligence) | A dashboard that maps a company's products to the job titles most likely to buy, plus competitors to watch. | Website analysis → ICP inference → structured output a PMM can act on. |
| [**Minglish**](https://github.com/Twishnoff/Minglish) | Professional-English practice for native Mandarin speakers. | Analyzes word pronunciation and generates practice words based on user performance.  |

## How I work

- **Craft with empathy.** Everything I build starts with asking "who is this for, and what am I trying to help them accomplish?". Nothing gets built without a plan and goal.
- **Build for production.** Mktforge has real users; the build log reports real activation and reply rates, including the misses.
- **Buy, build or skip — working within budget.** I develop scalable systems that care about revenue. I'm always working to bring down the costs of anything I build without sacrificing usability or security.
- **Applying contracts over conventions.** Analytics event taxonomy is documented and CI enforced: event that aren't in the contract fail the build.

## Stack

Claude API · Cloudflare Workers, Queues & KV · GitHub Actions · PostHog · HubSpot API & workflows · Clay · Apollo · Zapier · BigQuery · dbt · Firebase

## Elsewhere

[Portfolio](https://twishnoff.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/wishnoff) · [mktforge.io](https://mktforge.io)
