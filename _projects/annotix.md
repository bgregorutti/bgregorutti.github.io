---
layout: single
title: "Annotix"
excerpt: "Graph machine learning and molecular networking to annotate unknown molecules from LC-MS/MS spectra in analytical chemistry."
domain: "Analytical Chemistry · Cheminformatics"
status: "In progress"
order: 3
author_profile: true
header:
  overlay_color: "#0d2137"
  overlay_filter: 0.6
---

## Overview

**Annotix** is a machine learning project applied to **analytical chemistry**, targeting one of the core challenges in metabolomics: annotating unknown molecules from mass spectrometry data (LC-MS/MS).

In untargeted metabolomics experiments, only a fraction of detected compounds can be identified using standard databases. The goal of Annotix is to propagate annotations across a **molecular network** — exploiting spectral similarity between compounds to transfer known annotations to structurally related unknowns.

---

## Partners

| Institution | Role |
|---|---|
| [Observatoire Océanologique de Banyuls](https://obs-banyuls.fr) | Marine chemistry, LC-MS/MS data, scientific lead |
| SCAI | ML pipeline, molecular networking |

---

## My Role

I lead the ML and data science work on the project, and supervise a Master's intern working on the annotation pipeline.

**Responsibilities:**
- Design of the molecular networking and annotation propagation pipeline
- Selection and adaptation of graph ML methods for spectral data
- Supervision of an internship on the cheminformatics components
- Coordination with chemists at Banyuls on domain requirements and data

---

## Technical Approach

The pipeline combines several components:

1. **Spectral similarity computation** — pairwise similarity between MS/MS spectra using cosine similarity and modified cosine metrics (via `matchms`)
2. **Molecular network construction** — building a graph where nodes are spectra and edges reflect spectral similarity above a threshold (via `NetworkX`)
3. **Label propagation** — propagating known annotations across the network to candidate unknowns using graph-based semi-supervised learning
4. **Graph ML** — experimenting with GNN-based approaches (Graph Convolutional Networks) to predict molecular classes from spectral embeddings

**Stack**: Python · matchms · NetworkX · PyTorch Geometric · RDKit · pandas

---

## Scientific Context

Untargeted metabolomics generates thousands of features per sample, the vast majority of which remain unannotated. Molecular networking (popularised by the GNPS platform) groups related compounds visually, but annotation still relies heavily on manual curation. Annotix aims to automate and scale this process using ML, with a focus on marine natural products — a chemically rich and underexplored domain.

---

## Status

🟡 **In progress** — spectral similarity pipeline and network construction are operational; annotation propagation and GNN components under active development.

---

## Links

- [matchms library](https://matchms.readthedocs.io)
- [GNPS platform](https://gnps.ucsd.edu)
- [Observatoire de Banyuls](https://obs-banyuls.fr)
