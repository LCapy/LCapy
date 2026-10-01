# Lucas Melo

Solutions Engineer, AI Systems, Customer Delivery & Technical Integration, at Acolad.

I turn ambiguous enterprise requirements into shipped production systems: LLM-powered
tooling (including a RAG-based application), unified automation platforms, and the
Kubernetes infrastructure that runs them unattended in production.

## What I build

At Acolad, I architected and deployed a unified automation platform (CLI, desktop app, and
web control panel) that manages large-scale localization project lifecycles end to end, used
daily across thousands of files and multiple enterprise programs from one shared codebase.
That includes:

- A FastAPI web control panel backed by a Postgres job queue and a real-time, webhook-driven
  event pipeline (HMAC-verified deliveries, with a reconciliation sweep for full audit
  coverage)
- Around 20 scheduled Kubernetes CronJobs (EKS, Helm, GitHub Actions CI/CD) automating status
  tracking, QA sweeps, and delivery workflows across dev and production environments
- An LLM pipeline for automated transcription, QA, and client delivery: ASR transcription,
  human-in-the-loop review, forced word-level alignment, and delivery sanity checks, all
  tracked through one unified data model
- A RAG-based tool and an AI-assisted post-editing and terminology toolkit, enriching
  translation workflows with glossary data, fuzzy matches, and contextual segments
- TMS integrations and REST API workflows across enterprise systems, defining segmentation
  rules, token validation, and import/export formats

Most of this lives in private client repos, so what's public here is personal research.

## Featured project

**[embedding-rhizome-classifier](https://github.com/LCapy/embedding-rhizome-classifier)**
Independent research project and production API: multilingual (109-language) text
classification built on embedding-space geometry instead of a trained model, using
centroid-based similarity scoring, oblique projection, and topological path coherence over a
self-designed 238-node taxonomy. Wrote the research paper, built the scoring engine, and
deployed it as a live FastAPI service.

**[ICU-Validator](https://lcapy.github.io/ICU-Validator/)**
Browser-based tool for validating ICU message strings inside localization packages: strips
comments, checks ICU plural/select syntax, and produces a PDF error report. No backend, runs
entirely client-side.

## Stack

Python, JavaScript/Node.js, FastAPI, PostgreSQL, Kubernetes (EKS), Docker, AWS (S3, IAM),
GitHub Actions, LLM/RAG pipelines, embeddings and NLP (LaBSE, ASR, forced alignment).

---

![GitHub stats](https://github-readme-stats.vercel.app/api?username=LCapy&show_icons=true&theme=default&hide_title=true)
