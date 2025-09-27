RAG-based Document Q&A (Hybrid RAG with Metrics)
This repository contains a production‑ready Retrieval‑Augmented Generation (RAG) system with a React (Vite + TypeScript + Tailwind) frontend and a FastAPI backend. It supports PDF upload, hybrid retrieval (vector + BM25) with lightweight intent‑aware re‑ranking, citation highlighting, multilingual queries, and a full metrics/benchmarking suite.

Key Features

.Document upload and parsing (PDF → chunks → embeddings)/
.Hybrid retrieval: vector search + BM25, optional re‑rank/
.Faithful answers with inline citations and source preview/
.Multilingual question handling (normalize/translate → cite original spans)/
.Metrics and reports: Recall@5, Faithfulness, p95 latency, load test/
.API docs (OpenAPI) and Postman collection under API Docs/
