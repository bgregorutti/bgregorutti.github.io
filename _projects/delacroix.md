---
layout: single
title: "Digital Delacroix"
excerpt: "Computer vision applied to art history — digitising and analysing the complete works of Eugène Delacroix."
domain: "Art History · Digital Humanities"
status: "In progress"
order: 1
author_profile: true
header:
  overlay_color: "#2c1810"
  overlay_filter: 0.6
---

## Overview

The **Digital Delacroix** project applies computer vision and digital humanities methods to the full corpus of works by the French painter Eugène Delacroix. The goal is to build a structured, searchable digital archive that supports art history research at scale.

The project is funded by the **Schmidt Family Foundation** and involves a broad consortium of institutions.

---

## Partners

| Institution | Role |
|---|---|
| [Centre André-Chastel](https://www.centrechastel.sorbonne-universite.fr) | Art history expertise, corpus curation |
| [Assemblée Nationale](https://www.assemblee-nationale.fr) | Access to institutional collections |
| [ObTIC](https://obtic.sorbonne-universite.fr) | Digital humanities and text/image processing |
| [LAMS](http://www.umr-lams.fr) | Materials science, pigment analysis |
| SCAI | Data science and computer vision lead |

Funding: **Schmidt Family Foundation**

---

## My Role

I helped design and build the project from its early stages, and lead the data science component. My team includes two research engineers working on the vision pipeline.

**Responsibilities:**
- Project design and scientific scope definition
- Leading the data science team (2 engineers)
- Architecture of the computer vision pipeline
- Coordination with art history and digital humanities partners

---

## Technical Approach

- **Image digitisation and preprocessing**: standardisation of scans from heterogeneous sources (museums, private collections, archives)
- **Object detection and segmentation**: identifying motifs, figures, and compositional elements across the corpus
- **Similarity search**: finding visual patterns and recurring elements across paintings
- **Metadata enrichment**: linking image analysis results to structured art-historical metadata

**Stack**: Python · PyTorch · Torchvision · FAISS · OpenCV

---

## Status

🟡 **In progress** — active development across the image processing pipeline and the archive platform.

---

## Links

- [Project website](https://delacroix.sorbonne-universite.fr)
- [Centre André-Chastel](https://www.centrechastel.sorbonne-universite.fr)
- [ObTIC](https://obtic.sorbonne-universite.fr)
