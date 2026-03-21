---
layout: single
title: "Cowspiracy"
excerpt: "Computer vision for large-scale animal detection to study soil erosion and land degradation in Senegal and the Gobi Desert."
domain: "Ecology · Remote Sensing"
status: "In progress"
order: 2
author_profile: true
header:
  overlay_color: "#2d4a1e"
  overlay_filter: 0.6
---

## Overview

**Cowspiracy** is an ecology project using computer vision to automatically detect and count animals (cattle, goats, camels) in large collections of field images and remote sensing data. The goal is to quantify grazing pressure as a driver of **soil erosion** and **land degradation** in two environments: the **Sahel region of Senegal** and the **Gobi Desert**.

Understanding the spatial and temporal distribution of livestock at scale is a key challenge for researchers studying desertification — this project provides ML tooling to address it.

---

## Partners

| Institution | Role |
|---|---|
| [iEES Paris](https://iees-paris.fr) | Ecology, field data, scientific lead |
| [IRD](https://www.ird.fr) | Field campaigns in Senegal, remote sensing data |
| SCAI | Computer vision, ML pipeline |

---

## My Role

I lead the data science component of the project, working directly with ecologists at iEES Paris and IRD.

**Responsibilities:**
- Design of the detection pipeline (model selection, training strategy, evaluation)
- Coordination between ML engineers and domain scientists
- Handling domain-specific challenges: heterogeneous image sources, class imbalance, rare species

---

## Technical Approach

- **Detection model**: fine-tuned object detection model (YOLO-based) on annotated field images
- **Training data**: manually annotated image sets from field campaigns in Senegal and Mongolia
- **Scalability**: batch inference over large image collections (thousands of images per campaign)
- **Outputs**: animal counts, spatial density maps, temporal trends

**Stack**: Python · PyTorch · Ultralytics YOLO · GDAL · GeoPandas

---

## Scientific Context

Overgrazing is one of the main drivers of desertification in the Sahel and Central Asian steppes. Automated detection tools allow researchers to move from labour-intensive manual counting to systematic, reproducible monitoring at the landscape scale — enabling long-term ecological studies that were previously infeasible.

---

## Status

🟡 **In progress** — detection models are trained and under evaluation; integration with spatial analysis pipeline ongoing.
