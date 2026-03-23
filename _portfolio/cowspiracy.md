---
title: "Cowspiracy"
excerpt: "Computer vision for large-scale animal detection to monitor soil erosion and land degradation in Senegal and the Gobi Desert."
order: 2
domain: "Ecology"
status: "In progress"
collection: portfolio
---

## Overview

**Cowspiracy** uses computer vision to automatically detect and count animals (cattle, goats, camels) in large collections of field images. The goal is to quantify grazing pressure as a driver of **soil erosion** and **land degradation** in two regions: the **Sahel (Senegal)** and the **Gobi Desert**.

## Partners

| Institution | Role |
|---|---|
| [iEES Paris](https://iees-paris.fr) | Ecology, field data, scientific lead |
| [IRD](https://www.ird.fr) | Field campaigns in Senegal, remote sensing data |
| SCAI | Computer vision, ML pipeline |

## My Role

Lead the data science component, working directly with ecologists at iEES Paris and IRD. Responsible for detection pipeline design, modelling strategy and evaluation. Implement detection YOLO-based models.

## Technical Approach

- **Detection model**: fine-tuned YOLO-based object detection on annotated field images
- **Training data**: manually annotated images from field campaigns in Senegal
- **Scalability**: batch inference over thousands of images per campaign
- **Outputs**: animal counts, temporal trends

**Stack**: Python · PyTorch · Ultralytics YOLO

## Scientific Context

Automated detection tools allow researchers to move from labour-intensive manual counting to systematic, reproducible landscape-scale monitoring — enabling long-term ecological studies on desertification that were previously infeasible.

## Status

🟡 **In progress**
