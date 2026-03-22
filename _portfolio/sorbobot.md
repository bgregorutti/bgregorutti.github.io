---
title: "Sorbobot"
excerpt: "An LLM-based system for mapping and surfacing expertise across Sorbonne University using retrieval-augmented generation."
order: 4
domain: "NLP · Knowledge Management"
status: "Completed (SCAI phase)"
collection: portfolio
---

## Overview

**Sorbobot** helps researchers, students, and partners **discover expertise within Sorbonne University**. Given a research topic or question, the system surfaces relevant researchers, labs, and publications across the university's broad disciplinary landscape.

## Partners

| Institution | Role |
|---|---|
| [SUMMIT](https://summit.sorbonne-universite.fr) | Engineering team, infrastructure, data owner |
| SCAI | ML/NLP expertise, LLM pipeline, internship supervision |

## My Role

Contributed NLP and LLM architecture expertise (RAG pipeline design), mentored junior engineers, supervised one Master's intern, and coordinated with a freelance senior data engineer.

## Technical Approach

- **Data ingestion**: researcher profiles, lab pages, publication databases (HAL)
- **Indexing**: embedding-based vector index over researcher and publication content
- **RAG pipeline**: user queries matched against the index; retrieved context passed to an LLM for synthesis
- **Entity linking**: connecting researcher, lab, and topic mentions across heterogeneous sources

**Stack**: Python · LangChain / LlamaIndex · OpenAI / Mistral APIs · FAISS · PostgreSQL

## Status

🟢 **SCAI phase completed** — prototype built and validated. Project continues under SUMMIT's ownership.
