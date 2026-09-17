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

Target: fully "stacked" across Tracks A–D by **mid-to-late Feb 2027** — well ahead of a March 2027 full-time application push, with buffer for portfolio polish and interview prep. (Not realistic before the 11/1/2026 deadline on any single posting like Deloitte's — the required-qualifications bar is covered by Track A/B well before then; the differentiators above are a deliberate longer-term bet, not a same-quarter fix.)

### Track E — Delegated to External Resources

Genuinely lowest priority, pointer-only unless a specific job posting demands it:

- **Snowflake/BigQuery** — cheapest to add since it's mostly SQL knowledge transferring directly. Quick pass right after Track B wraps, **~late Oct 2026** — only the cloud-specific differences get covered.
- **Spark** — pointer to a course/cert only; revisit if it shows up repeatedly in postings for targeted roles.
- **Project management (Jira + Agile/Scrum)** — genuinely valuable across Data Analyst, BI Engineer, and consulting-style roles (client/cross-functional coordination, sprint planning), and Ryan's actively exploring it. Jira is the most broadly relevant tool for data/tech-adjacent teams specifically; a short Agile/Scrum fundamentals certificate (e.g. Scrum Fundamentals Certified, or the Google Project Management Certificate for broader PM methodology) is the efficient way in, rather than a deep-taught module here.

### Staying Self-Directed

Power BI/Tableau (basic knowledge already, kept warm independently), case-interview prep, Git/GitHub (learned informally throughout, not a discrete track).

### Staying Current

Once Tracks A–D are solid, this roadmap doesn't freeze — periodically re-scan what's actually in demand for the targeted roles (job postings, industry trend reports) and fold newly-relevant tools/skills into the study list, so the plan keeps adapting rather than going stale. This is an ongoing process, not a one-time pass.

*Last updated: 2026-09-17*
