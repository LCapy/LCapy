![Lucas Melo](banner.svg)

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

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
