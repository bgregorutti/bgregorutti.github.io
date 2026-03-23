---
title: "Annotix"
excerpt: "Graph machine learning and molecular networking to annotate unknown molecules from LC-MS/MS spectra in metabolomics."
order: 3
domain: "Analytical Chemistry · Cheminformatics"
status: "In progress"
collection: portfolio
---

## Overview

**Annotix** addresses one of the core challenges in untargeted metabolomics: annotating unknown molecules from mass spectrometry data (LC-MS/MS). The approach uses **molecular networking** — exploiting spectral similarity between compounds to propagate known annotations to structurally related unknowns.

## Partners

| Institution | Role |
|---|---|
| [Observatoire Océanologique de Banyuls](https://obs-banyuls.fr) | Marine chemistry, LC-MS/MS data, scientific lead |
| SCAI | ML pipeline, molecular networking |

## My Role

Lead the ML and data science work.

**Responsibilities:** pipeline design, graph ML method selection, cheminformatics component supervision, coordination with chemists on domain requirements.

## Technical Approach

1. **Spectral similarity** — pairwise cosine and modified cosine similarity between MS/MS spectra
2. **Molecular network** — graph where nodes are spectra and edges reflect spectral similarity above a threshold
3. **Label propagation** — propagating known annotations to unknown compounds via graph-based semi-supervised learning
4. **Graph ML** — GNN-based (Graph Convolutional Networks) prediction of molecular classes from spectral embeddings

**Stack**: Python · Matchms · NetworkX · RDKit

## Scientific Context

Molecular networking (popularised by [GNPS](https://gnps.ucsd.edu)) groups related compounds visually, but annotation still relies heavily on manual curation. Annotix aims to automate this at scale, with a focus on marine natural products — a chemically rich and underexplored domain.

## Status

🟡 **In progress**
