# Data Journey

Documenting my path to becoming a Data Scientist / AI Engineer — Python, SQL, Pandas, EDA, and ML fundamentals through real projects and Kaggle competitions, working toward Data Scientist / Data Analyst / AI Engineer / Business Analyst / BI Engineer roles.

Studying ~15 hrs/week. Dates below are estimates based on that pace, not commitments — they'll shift as topics take more or less time than expected.

## Contents

- [`pandas_numpy_and_comprehensions.ipynb`](pandas_numpy_and_comprehensions.ipynb) — core fundamentals notebook (Python logic → NumPy → Pandas). Concept notes are documented inline as markdown cells alongside the code that motivated them.
- [`titanic/`](titanic/) — Kaggle Titanic dataset (`train.csv`, `test.csv`, `gender_submission.csv`). Used as the running example from Pandas fundamentals through the eventual Kaggle competition submission.

## Roadmap

### Track A — Core Analytics

| # | Topic | Status | Dates |
|---|-------|--------|-------|
| 1 | Python logic fundamentals | ✅ Done | — |
| 2 | NumPy fundamentals | ✅ Done | — |
| 3 | Pandas fundamentals (boolean filtering, `groupby`, missing data, `.loc`/`.iloc`) | ✅ Done | 2026-09-16 |
| 4 | EDA & basic stats (distributions, correlation, Matplotlib/Seaborn/Plotly) | Next | 2026-09-16 → 2026-09-22 |
| 5 | scikit-learn fundamentals (train/test split, fit/predict, evaluation metrics, data leakage) | Planned | 2026-09-23 → 2026-10-06 |
| 6 | **Titanic Kaggle competition, end-to-end** (first concrete milestone) | Planned | 2026-10-07 → 2026-10-20 |
| 7 | More Kaggle competitions | Planned | 2026-10-21 → ongoing |

### Track B — SQL

Interleaved with Track A rather than run strictly after it, so Python/Pandas skills stay active. Starting from real fundamentals — not assuming prior coursework counts.

| # | Topic | Status | Dates |
|---|-------|--------|-------|
| 8 | SQL fundamentals (baseline check → joins, aggregation, subqueries, window functions) | Planned | 2026-09-16 → 2026-10-20 |
| 9 | DuckDB | Planned | 2026-10-21 → 2026-10-27 |
| 9.5 | BigQuery (GCP data warehouse — SQL dialect differences, querying at scale) | In Progress | 2026-09-24 → ongoing |

### Track B.5 — Technical Interview Prep (Python/SQL, LeetCode-style)

Added 2026-09-19 after a rough first technical coding interview — went in with no structured practice, want to fix that gap directly rather than assume Track A/B fluency transfers to interview conditions under time pressure. Runs interleaved with Tracks A/B (not blocking them), starting at fundamentals and ramping difficulty, with the goal of being genuinely interview-ready by **mid-Oct to Nov 2026**. Practice here is supplemented independently with self-driven LeetCode reps outside of lesson sessions.

| # | Topic | Status | Dates |
|---|-------|--------|-------|
| B.5 | Python + SQL interview questions, basic → intermediate → hard, timed/interview-style practice | In Progress | 2026-09-19 → 2026-11-30 |

**Practice platforms (DS-specific, beyond LeetCode):**
- **StrataScratch** — real DS/analytics interview questions pulled from actual companies (Meta, Amazon, etc.), strong SQL + Python/Pandas coverage
- **DataLemur** — SQL-focused, questions tagged by real company + difficulty, good for timed drilling
- **Interview Query** — DS/ML-specific interview questions including SQL, Python, stats, and case-style questions, closer to actual DS interview format than general coding platforms
- LeetCode itself is still worth using for the general coding-interview muscle (arrays, strings, algorithms) most technical screens include regardless of DS focus — but its "Database" section alone under-represents what real DS SQL rounds look like compared to the platforms above.

### Track C — AI/ML Differentiation

The actual "ahead of the curve" bet for AI Engineer roles — most DA/DS candidates stop at classical ML. **Agentic AI moved first**, ahead of PyTorch — it's the single most-emphasized "stand out" skill in current AI Engineer postings (e.g. Deloitte's Data & AI Solutions Engineering Analyst posting, reviewed 2026-09-17: "building AI-powered systems that observe, decide, and act with autonomy"), and it doesn't actually require deep learning fundamentals first — it's mostly API use, prompting, and orchestration.

| # | Topic | Status | Dates |
|---|-------|--------|-------|
| 10 | Agentic AI fundamentals + project (LLM tool use, decision loops, guardrails/audit trails) | Planned | 2026-10-21 → 2026-11-10 |
| 11 | PyTorch | Planned | 2026-11-11 → 2026-12-08 |
| 12 | Hugging Face / LLM fundamentals (deepen: model internals, fine-tuning) | Planned | 2026-12-09 → 2026-12-29 |

### Track D — Cloud & MLOps/Deployment

Elevated from a "someday" pointer to a properly taught track — postings like Deloitte's list cloud platform familiarity as a **required** qualification (not just preferred), and MLOps/CI-CD as explicitly preferred. Cloud fundamentals (compute, storage, IAM, managed services) overlap heavily across AWS/Azure/GCP, so taught once as transferable concepts with platform-specific differences flagged, rather than three separate deep-dives. Docker folds in here too, as part of the deployment pipeline work, rather than waiting on an unrelated trigger.

| # | Topic | Status | Dates |
|---|-------|--------|-------|
| 13 | Cloud fundamentals — AWS, Azure, GCP (transferable core concepts + key differences) | Planned | 2026-12-30 → 2027-01-26 |
| 14 | MLOps, CI/CD & deployment (Docker, MLflow/experiment tracking, deploying one model through a real pipeline) | Planned | 2027-01-27 → 2027-02-16 |
| 15 | Vertex AI (GCP managed ML platform — training, pipelines, model deployment) | Planned | 2027-02-17 → 2027-03-02 |
| 16 | Graph databases (e.g. Neo4j — modeling, Cypher queries, use cases like recommendations/fraud/knowledge graphs) | Planned | 2027-03-03 → 2027-03-16 |

Target: fully "stacked" across Tracks A–D by **mid-to-late Feb 2027** — well ahead of a March 2027 full-time application push, with buffer for portfolio polish and interview prep. (Not realistic before the 11/1/2026 deadline on any single posting like Deloitte's — the required-qualifications bar is covered by Track A/B well before then; the differentiators above are a deliberate longer-term bet, not a same-quarter fix.)

### Certifications

Layered onto Track D rather than a separate track — cloud fundamentals certs first (cheap, broad resume signal), then platform-specific, then the agentic-AI differentiator last once there's real hands-on practice behind it. C1 pulled forward — no prerequisites, runs fine in parallel with Track B (SQL/BigQuery).

| # | Cert | Status | Target |
|---|------|--------|--------|
| C1 | AWS Certified Cloud Practitioner (CLF-C02) | In Progress | 2026-09-25 → ongoing (parallel with Track B) |
| C2 | AZ-900 (Azure Fundamentals) | Planned | right after C1 — high overlap, cheap add-on |
| C3 | Databricks Certified (Data Engineer Associate or ML Associate — pick per target role) | Planned | after C1/C2, alongside Track D step 14 (MLOps), ~Feb 2027 |
| C4 | Claude Code Architect | Planned | last — after Track C (agentic AI) and real Claude Code usage, ~late Feb–Mar 2027 |

Also worth a beginner-friendly checkpoint alongside Track A/B: **DataCamp's "Associate Data Scientist in Python" career track + certification** — more structured/guided than this self-directed roadmap, good as a credential that validates the fundamentals already being built here.

### Track E — Delegated to External Resources

Genuinely lowest priority, pointer-only unless a specific job posting demands it:

- **Snowflake** — cheapest to add since it's mostly SQL knowledge transferring directly. Quick pass right after Track B wraps, **~late Oct 2026** — only the cloud-specific differences get covered. (BigQuery moved to Track B — in progress now.)
- **Spark** — pointer to a course/cert only; revisit if it shows up repeatedly in postings for targeted roles.
- **Project management (Jira + Agile/Scrum)** — genuinely valuable across Data Analyst, BI Engineer, and consulting-style roles (client/cross-functional coordination, sprint planning), and Ryan's actively exploring it. Jira is the most broadly relevant tool for data/tech-adjacent teams specifically; a short Agile/Scrum fundamentals certificate (e.g. Scrum Fundamentals Certified, or the Google Project Management Certificate for broader PM methodology) is the efficient way in, rather than a deep-taught module here.

### Staying Self-Directed

Power BI/Tableau (basic knowledge already, kept warm independently), case-interview prep, Git/GitHub (learned informally throughout, not a discrete track). CS50P (Harvard's free Python course) running independently alongside Track B.5 for structured fundamentals review, addressing gaps surfaced during interview-style practice (e.g. loop-by-index, `range()` mechanics, list indexing).

**Hackathons** — register and participate opportunistically as they come up (Devpost, Kaggle competitions, local/university events), not a scheduled track. Cheap way to build portfolio projects, get exposure to real time-boxed problem-solving, and network.

### External Resources

- **[awesome-datascience](https://github.com/academic/awesome-datascience#where-do-i-start)** — beginner roadmap reference; validated 2026-09-21 that Track A's sequencing (Python → NumPy/Pandas → EDA/stats → scikit-learn → Kaggle project) already matches its recommended order
- **CS50P** (Harvard, free, edX/YouTube) — structured Python fundamentals, used for interview-prep gap-filling (Track B.5)
- **W3Schools Python** — quick syntax reference/lookup while coding
- **Math basics (stats, probability, linear algebra)** — not yet a dedicated track; currently folded into Track A step 4 (EDA & basic stats). Flagged as a gap vs. the awesome-datascience roadmap, which lists math as its own step before ML — revisit if Track A step 5 (scikit-learn) surfaces concepts that need more grounding than EDA alone provides.

### Staying Current

Once Tracks A–D are solid, this roadmap doesn't freeze — periodically re-scan what's actually in demand for the targeted roles (job postings, industry trend reports) and fold newly-relevant tools/skills into the study list, so the plan keeps adapting rather than going stale. This is an ongoing process, not a one-time pass.

*Last updated: 2026-09-17*
