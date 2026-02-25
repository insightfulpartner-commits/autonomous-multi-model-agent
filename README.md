# Autonomous Multi‑Model Agent

This repository contains the codebase for an autonomous multi‑model agent system, including:

- Multi‑agent orchestration
- Reasoning loop worker
- API service (FastAPI)
- Retrieval and embeddings pipeline
- Vector search integration (Qdrant)
- Supabase Postgres schema and storage
- Cloudflare Zero‑Trust + DNS
- Fly.io deployment configuration

## Deployment Targets

- Fly.io (API + Worker)
- Supabase (Database + Auth + Storage)
- Qdrant Cloud (Vector DB)
- Cloudflare (DNS + TLS + Zero‑Trust)
- HuggingFace Inference API (Lightweight tasks)
- OpenAI / Anthropic (Heavy reasoning)

## Status

Initial commit to enable GitHub → Fly.io integration.
