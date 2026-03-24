---
title: "Real-Time Graph Clustering for Network Intrusion Detection"
excerpt: "Online graph clustering for detecting suspicious activities in computing systems — applied to the DARPA OpTC dataset, funded by the DGA Cyberdefence Factory."
order: 6
company: "LumenAI"
domain: "Cybersecurity · Graph Machine Learning"
status: "Completed — published"
collection: portfolio
---

## Overview

This project, carried out at **LumenAI** and funded by the **DGA Cyberdefence Factory** program (Rennes), proposes an online graph clustering approach for **real-time network intrusion detection**. The core idea: cyberattacks dynamically create abnormal connections between system processes — detecting the resulting anomalous communities in the network graph reveals the intrusion.

The work was validated on the publicly available **OpTC dataset**, provided by the **Defense Advanced Research Projects Agency (DARPA)**, and resulted in a peer-reviewed publication.

---

## Problem

Traditional intrusion detection systems rely on static signatures or threshold-based rules, which struggle against novel or adaptive attacks. A more robust approach is to model the system as a dynamic graph — where nodes are processes and edges are interactions — and detect anomalies in the evolving community structure of that graph in real time.

---

## Approach

**Graph construction**
System activity (process interactions, network connections, file accesses) is modelled as a dynamic graph. Each event in the audit log creates or modifies an edge between two nodes (processes or resources).

**Online community detection**
Rather than processing snapshots of the full graph offline, the algorithm maintains and updates community structure incrementally as new events arrive — enabling detection latency compatible with real operational environments.

**Intrusion detection via community anomalies**
Attacks manifest as abnormal clusters of activity — processes that would not normally communicate begin forming tight communities. Detecting these anomalous communities flags potential intrusions.

**Evaluation on DARPA OpTC**
The approach was evaluated on the OpTC (Operational Transparent Computing) dataset, a large-scale publicly available benchmark of realistic enterprise network activity with injected attack scenarios, released by DARPA.

---

## My Role

I led the technical team at LumenAI responsible for the R&D and prototype implementation.

**Responsibilities:**
- Supervised the research direction and algorithm design
- Oversaw prototype implementation and evaluation on the OpTC dataset
- Co-supervised a PhD student, co-author of the publication

---

## Results

Preliminary results demonstrate the **feasibility of real-time graph clustering for intrusion detection**, with the OpTC dataset providing a challenging and realistic benchmark. The work establishes a foundation for an end-to-end intelligent attack detection system.

---

## Publication

> *Real-time graph clustering for network intrusion detection.*
> Proceedings of Conference on Artificial Intelligence for Defense, 2021
> **Keywords**: Real-time · Graph clustering · Intrusion detection.

---

## Stack

Python · NetworkX · online graph algorithms · community detection