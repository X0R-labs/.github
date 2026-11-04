<div align="center">

<img src="https://github.com/X0R-labs.png" width="96" alt="X0R Labs" />

# X0R Labs

**AI software, built to be the difference.**

We design, build and ship AI systems that take the hard part out of someone's work —
and we hand over the keys.

[Website](https://xor.ct.ws) · [LinkedIn](https://www.linkedin.com/company/x0r-labs) · [hello@x0rlabs.com](mailto:hello@x0rlabs.com)

</div>

---

## What we build

| | |
| --- | --- |
| **AI products** | Focused tools around a single job, taken from prototype to something people use daily. |
| **Custom AI systems** | Models, retrieval pipelines and agents shaped around your data and your workflow. |
| **Rapid prototypes** | A working thing in weeks, not quarters. Keep what works, cut what doesn't. |

The name is the logic gate: XOR returns true only when its two inputs differ. It is how we
work — we build the part that makes your product *not* the same as everyone else's.

## Featured: X0R Core

**The AI agent backend you own.** Self-hosted, provider-agnostic, metered.

Most teams building an AI feature rebuild the same six things — ingestion, retrieval, a tool
loop, tenant auth, usage accounting, and evals — then couple all of it to one vendor.

X0R Core is those six things, written once. FastAPI + SQLAlchemy. SQLite for a demo,
Postgres for production. Point it at OpenAI, OpenRouter, Groq, vLLM or a local Ollama and
it behaves the same.

```bash
pip install -e ".[dev]"
x0r seed     # demo workspace + agent + eval suite
x0r serve    # http://127.0.0.1:8000/docs
```

- **Ingest** — paragraph-aware chunking, embeddings, hybrid retrieval
- **Agents** — bounded tool loop with a registry you can extend
- **Meter** — API keys, workspace quotas, per-run token accounting
- **Prove** — eval suites with per-case scores and pass rates

[**Read the code →**](https://github.com/X0R-labs/core) · Apache-2.0

## How we work

1. **Prototype** — the idea becomes something you can click, in weeks rather than quarters.
2. **Build** — the real thing, in small releases you can see land.
3. **Ship and improve** — launch, measure what people actually use, keep improving it.

## Work with us

| Engagement | Shape | From |
| --- | --- | --- |
| **Discovery sprint** | One week. Ranked use cases, data audit, a working prototype. | $2,500 |
| **Pilot build** | Four weeks. One workflow, on your data, in production. | $12,000 |
| **Care & scale** | Monthly. Deployment, monitoring, evals, improvements. | $2,000/mo |

We are a small team and we take a limited number of builds at a time. If the problem is
interesting, say hello: **[hello@x0rlabs.com](mailto:hello@x0rlabs.com?subject=Project%20enquiry)**

---

<sub>© 2026 X0R Labs · Built remote, shipped worldwide</sub>
