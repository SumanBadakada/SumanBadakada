# Hi, I'm Suman Somaiah 👋

**Engineer turned AI product builder.** Five years shipping production systems on First American's primary revenue platform, now building applied AI products while completing an MBA + MS in Digital Technology at Boston University Questrom (May 2027).

- 🔭 Building AI agents and retrieval-backed assistants that work in real workflows
- ☁️ Led the technical side of a legacy-to-AWS serverless migration: 90% less downtime, 35% lower maintenance cost
- 🎤 World Championship of Public Speaking quarter-finalist, and a musician with 450+ live shows
- 📫 [LinkedIn](https://www.linkedin.com/in/sumansomaiahba) · suman97@bu.edu

---

## Featured projects

### ⚖️ [Boston Lease Checker](https://github.com/SumanBadakada/IS883_bostonleasechecker) · [live app](https://bostonleasechecker.streamlit.app/)
Upload a Boston lease and get every clause flagged *lawful*, *unusual* or *possibly unlawful* under Massachusetts tenant law, each with a citation, plus a check of move-in charges against legal limits.
- Retrieval over Massachusetts statutes and regulations, so every citation points at a passage the model was given
- Gemini tool calling for the move-in charge check, and schema-validated structured output with retry and graceful failure
- Evaluation harness over 20 labeled leases and edge cases, reporting recall on unlawful clauses, citation accuracy and cost per lease
- `Python` `Streamlit` `Gemini` `Pydantic` `NumPy` · team project, IS883 (Fall 2026)

### 🏙️ [311 Pulse: Boston](https://github.com/SumanBadakada/boston-311-pulse)
Weekly operations brief for Boston city managers from 550K+ 311 service requests: what's surging, which departments are falling behind, which neighborhoods are served worse than their request mix predicts, and which problems keep coming back.
- Poisson-scored surge detection, as-of-date replay of any past week, mix-adjusted on-time gap by neighborhood
- AI-written brief where every number is checked against the computed facts; drafts with untraceable figures are discarded
- `Python` `pandas` `Streamlit` `Claude API` · extends a team Tableau project from Analytics for Managers

### 🛰️ [ci-watch](https://github.com/SumanBadakada/ci-watch)
Competitive intelligence refresh agent. Watches competitor pages, decides which changes matter, rewrites only the affected section of a sales battlecard, and routes every edit through human approval.
- Normalise-then-diff pipeline with cheap filters before any model call, so a nightly run over dozens of vendors stays affordable
- LLM materiality classifier tuned for asymmetric error cost: a missed price change is worse than a false alarm
- Approve/reject review queue with a changelog, idempotent re-runs, offline demo and tests in CI
- `Python` `Claude API` `GitHub Actions`

---

## Tech I work with

**AI:** LLM tool calling, retrieval (RAG), structured output, evaluation, prompt versioning
**Backend & cloud:** Python, Java, SQL, REST APIs, AWS (EC2, S3, Fargate, OpenSearch), Docker, Kubernetes, CI/CD
**Front end & apps:** Streamlit, Flask, JavaScript, Angular, Chrome extensions

---

<sub>Currently: Research Assistant on AI-assisted feedback at BU Questrom · Previously: Software Engineer at First American, Product & Competitive Intelligence at MADTECH.AI</sub>
