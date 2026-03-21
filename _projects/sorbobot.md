---
layout: single
title: "Sorbobot"
excerpt: "An LLM-based system for mapping and surfacing expertise across Sorbonne University using retrieval-augmented generation."
domain: "NLP · Knowledge Management"
status: "Completed (SCAI phase)"
order: 4
author_profile: true
header:
  overlay_color: "#1a0a2e"
  overlay_filter: 0.6
---

## Overview

**Sorbobot** is an NLP and LLM project designed to help researchers, students, and partners **discover expertise within Sorbonne University**. Given a research topic or question, the system surfaces relevant researchers, labs, and publications across the university's broad disciplinary landscape.

The project addresses a real institutional challenge: Sorbonne is a large, decentralised university where expertise is difficult to navigate — both internally and for external partners seeking collaborators.

---

## Partners

| Institution | Role |
|---|---|
| [SUMMIT](https://summit.sorbonne-universite.fr) | Engineering team, infrastructure, data owner |
| SCAI | ML/NLP expertise, LLM pipeline, internship supervision |

---

## My Role

I contributed ML and LLM expertise throughout the SCAI phase of the project, working alongside SUMMIT's engineering team and a senior freelance data engineer.

**Responsibilities:**
- Brought NLP and LLM architecture expertise (RAG pipeline design)
- Mentored junior engineers on the team
- Supervised one Master's intern on the NLP components
- Coordinated with the freelance senior data engineer on the data pipeline

---

## Technical Approach

- **Data ingestion**: structured and unstructured sources (researcher profiles, lab pages, publication databases, HAL)
- **Indexing**: embedding-based vector index over researcher and publication content
- **Retrieval-Augmented Generation (RAG)**: user queries are matched against the index; retrieved context is passed to an LLM for synthesis
- **Entity linking**: connecting mentions of researchers, labs, and topics across heterogeneous sources

**Stack**: Python · LangChain / LlamaIndex · OpenAI / Mistral APIs · FAISS · PostgreSQL

---

## Status

🟢 **SCAI phase completed** — the system prototype was built and validated during SCAI's involvement. The project continues under SUMMIT's ownership.
