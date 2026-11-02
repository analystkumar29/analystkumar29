### Hi, I'm Manoj — developer & data analyst in Burnaby, BC

I build and run production web systems: a booking and dispatch platform for my own repair business, AI chat and voice agents that work from live data, and a privacy-first data product used by people waiting on immigration decisions. I'm open to full-time **developer, data analyst and application support** roles in BC or remote. Canadian Permanent Resident, available now.

**[Portfolio](https://manojkumar-ca.vercel.app)** · **[Résumé (PDF)](https://manojkumar-ca.vercel.app/resume)** · **[LinkedIn](https://www.linkedin.com/in/meet-manoj/)** · **[Engineering notes](https://manojkumar-ca.vercel.app/notes)** · analystkumar29@gmail.com

---

#### Code you can open

| Repo | What it shows |
|---|---|
| **[ircc-processing-times](https://github.com/analystkumar29/ircc-processing-times)** | Python and pandas analysis of IRCC's official processing-time feed: 28 programs, 3,574 rows, tidy parsing with tests, five charts and written findings. |
| **[senate-tenure-survival](https://github.com/analystkumar29/senate-tenure-survival)** | Survival analysis with lifelines: Kaplan–Meier, log-rank and Cox models on 933 Canadian senators, and why ignoring censoring gives the wrong answer. |
| **[repair-shop-sql](https://github.com/analystkumar29/repair-shop-sql)** | Ten business questions answered in SQL (CTEs, window functions, cohorts, percentiles) on a seeded synthetic dataset modelled on a repair business. |
| **[supabase-fetch-all](https://github.com/analystkumar29/supabase-fetch-all)** | A tested TypeScript helper for a real production bug: Supabase silently stops every read at 1,000 rows. |
| **[portfolio](https://github.com/analystkumar29/portfolio)** | The source of my portfolio site: Next.js 16, React 19, Tailwind CSS 4, checked on every push. |

#### Live systems I built and run

The code for these is private because it runs real businesses and holds client and user data. Each one links to the live site and a full case study, and I'm happy to walk through the code on a call.

| Project | What it is | Built with | Results |
|---|---|---|---|
| **Travelling Technicians** · [live](https://www.travelling-technicians.ca) · [case study](https://manojkumar-ca.vercel.app/work/travelling-technicians) | Booking, payments, dispatch, warranty and AI-agent platform for my doorstep phone and laptop repair business | Next.js, TypeScript, Supabase PostgreSQL, Stripe, Cloudflare Workers, DeepSeek + Retell agents | ~9,000 generated SEO pages · 547K Google search impressions since Feb 2026 · 1,400+ commits |
| **Immigration Timeline** · [live](https://www.immigrationtimeline.ca) · [case study](https://manojkumar-ca.vercel.app/work/immigration-timeline) | Wait-time estimates shown as ranges, with a published methodology and a privacy floor | Next.js, TypeScript, Supabase, Python (pandas, lifelines) | 336 monthly active users in 33 countries · Kaplan–Meier model on 127,684 stage transitions |
| **Raba Thrift** · [live](https://www.rabathrift.ca) · [case study](https://manojkumar-ca.vercel.app/work/raba-thrift) | Client site: donation intake and a self-serve CMS for a Chilliwack thrift store | Next.js 16, Sanity, Supabase, Resend | 55 indexed pages · staff publish edits without a developer |

#### Engineering notes

- [The 1,000-row limit that quietly changed my prices](https://manojkumar-ca.vercel.app/notes/the-1000-row-limit-that-quietly-changed-my-prices)
- [Why a client's published CMS edits weren't reaching the live site](https://manojkumar-ca.vercel.app/notes/why-published-cms-edits-werent-reaching-the-live-site)
- [Refusing to compute below 25 people](https://manojkumar-ca.vercel.app/notes/refusing-to-compute-below-25-people)

#### How I build

I use AI coding agents (mostly Claude Code) as a pair programmer. I write the brief and the rules, review every change, write or check the tests, and verify the result in a browser before it ships. Commits made that way carry a `Co-Authored-By` line. I'm happy to explain any line of code I've published.

#### How I got here

After my B.Tech in computer science (2018) I worked in customer support in New Delhi, then studied data analytics at Langara College in Vancouver (2020). The next few years were restaurant operations and retail tech repair, ending as a store supervisor at London Drugs after earning Apple's ACMT and ACiT certifications. In 2024 I started my own doorstep repair business, built its software myself, and that work grew into everything above.

#### Skills

- **Data:** SQL / PostgreSQL · DuckDB · Python (pandas, scikit-learn, lifelines) · survival analysis · Power BI · Excel
- **Web:** TypeScript · React · Next.js · Node.js · Tailwind CSS · Supabase · Stripe · REST APIs and webhooks
- **AI:** Claude Code, Cursor and Codex · LLM tool calling · chat and voice agents · MCP servers
- **Also:** Git and GitHub Actions · pytest · Vitest and Jest · Docker · Vercel · IT support

**Education:** Post-Degree Diploma in Data Analytics, Langara College · B.Tech in Computer Science and Engineering, Maharshi Dayanand University
