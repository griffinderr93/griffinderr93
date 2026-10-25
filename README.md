# Hi, I'm Griffin Derr

Finance and Business Information Systems student at **TCU's Neeley School of Business** (Class of 2029). I'm interested in where consulting and AI meet: taking a messy business problem, breaking it into clear steps, and building software that actually helps people do the work.

I founded the **TCU Consulting Club**, consult for nonprofits with **SCNO**, and build most of my projects with Claude and AI agents.

---

## Currently building

**ClubOS: an AI platform for the TCU Consulting Club** *(in progress)*

The club runs on [tcuconsultingclub.com](https://tcuconsultingclub.com). ClubOS is the next version of it:

- **Multi-agent copilot.** A planner agent breaks a request like "plan our next speaker event" into steps, worker agents handle the task board, outreach log, and club knowledge through tool calls, and a critic agent reviews drafts before they go anywhere.
- **Hybrid RAG.** Keyword and vector search (Supabase + pgvector) over club documents, cases, and a firm library, with reranking and cited sources.
- **Human-approval queue.** Nothing goes out without an officer signing off.
- **Role-based access control, tracing, and an eval harness** so every agent run can be inspected and measured.
- **AI case interviewer** that runs practice cases and scores them against a rubric.
- **Member-to-firm matching**, evaluated with NDCG@10.

Stack: Next.js, TypeScript, Supabase/pgvector, Anthropic API.

| Metric | Result |
|---|---|
| Retrieval accuracy | TBD |
| Hallucination rate | TBD |
| Firm matching NDCG@10 | TBD |
| Median latency / cost per run | TBD |

*Eval results will be posted once the harness has run against the labeled test set.*

---

## Featured projects

| Project | What it does |
|---|---|
| **ClubOS** | Multi-agent AI platform for the TCU Consulting Club (in progress, see above) |
| **[TCU Consulting Club site](https://tcuconsultingclub.com)** | The club's platform, built with AI-assisted development |
| **Recruiting pipeline** | Tracks firms, contacts, and application stages for consulting recruiting |
| **Case interview trainer** | Practice tool for case interviews |
| **AI delegation scorecard** | Scores which tasks are a good fit to hand to AI and which need a person |
| **Golf handicap + strokes gained** | Turns a scorecard photo into a WHS handicap index, with a strokes-gained model |
| **Golf yardage + caddie tools** | Builds a yardage map from a Google Earth screenshot, plus green reading and swing video analysis |

**Consulting work:** As BIS project manager, I lead a 4-person team consulting for Lotus Technology on an AI-enabled transformation. We're designing 3 AI pilots, with targets of cutting forecast error by 20% and unplanned downtime by 20–30%.

---

## Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-E76F00?style=flat-square&logo=openjdk&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

**AI and web**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Anthropic API](https://img.shields.io/badge/Anthropic%20API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Analytics**

![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

---

## How I build with AI

- **Agents with clear jobs.** I run a small team of AI agents that each own one area: networking, school deadlines, inbox and calendar, and interview prep. Narrow roles are easier to trust and easier to debug.
- **A human signs off.** Agents can draft, plan, and research, but anything that leaves the system (an email, a post, a submission) waits for my approval. ClubOS uses the same rule through its approval queue.
- **Measure it.** "It seems to work" isn't enough. I build labeled test sets and eval harnesses so I can tell whether a change actually made the system better.
- **Understand what ships.** I use Claude to move fast, but I want to be able to explain every part of what I build.

Certified in **Anthropic AI Fluency**.

---

## Outside of code

- Consultant, **SCNO** (Students Consulting for Non-Profit Organizations)
- **TCU Sales Center** Consultative Selling Program
- Golf, which is why two of my apps are golf apps

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-griffinderr-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/griffinderr/)
[![Email](https://img.shields.io/badge/Email-griffin.j.derr%40tcu.edu-4D1979?style=flat-square&logo=maildotru&logoColor=white)](mailto:griffin.j.derr@tcu.edu)
[![Website](https://img.shields.io/badge/TCU%20Consulting%20Club-tcuconsultingclub.com-4D1979?style=flat-square)](https://tcuconsultingclub.com)
