---
title: "OptiFlight"
excerpt: "ML and optimisation algorithms for aircraft fuel consumption reduction across all flight phases — now deployed on thousands of aircraft worldwide."
order: 0
company: "Safety Line"
domain: "Aviation · Optimisation · Machine Learning"
status: "Deployed"
collection: portfolio
---

## Overview

**OptiFlight** is an end-to-end fuel optimisation system developed at Safety Line, covering all phases of a commercial flight — **climb, cruise, and descent**. The system combines machine learning, flight performance modelling, and real-time meteorological data to generate actionable recommendations for pilots and airlines.

The product is now deployed on **thousands of aircraft** by **SITA**, one of the world's leading aviation technology companies.

---

## Problem

Fuel is the largest operating cost for airlines — typically 20–30% of total expenses. Even small improvements in flight efficiency, compounded across thousands of flights per day, translate into significant savings and emissions reductions. The challenge is that optimal flight profiles are highly dependent on aircraft-specific performance, weather conditions, and air traffic constraints, making generic rules inadequate.

---

## Approach

**Tail-specific performance models**
Rather than relying on generic fleet-level models, the system learns individual performance profiles for each aircraft tail number from its own historical flight data. This captures aircraft-level ageing, maintenance state, and aerodynamic variability.

**Large-scale QAR data processing**
Models are trained on **millions of data points** from QAR (Quick Access Recorder) data — thousands of flights per airline client, with hundreds of parameters recorded each second. This required robust pipelines for data ingestion, decoding, cleaning, and feature engineering at scale.

**Real-time weather integration**
Optimisation is performed using actual weather forecasts (wind, temperature, pressure) along the planned route, enabling trajectory recommendations that are feasible under real atmospheric conditions rather than standard atmosphere assumptions.

**Multi-phase optimisation**
- **Climb**: optimal speed and thrust profiles to reach cruise altitude efficiently
- **Cruise**: optimal flight level and speed scheduling given winds aloft
- **Descent**: continuous descent approaches to minimise fuel burn

---

## My Role

I led the data science and engineering team responsible for developing the core ML and optimisation components of OptiFlight.

**Responsibilities:**
- Led a team of data scientists and engineers
- Designed and implemented ML algorithms for tail-specific performance modelling
- Built the large-scale QAR data processing pipeline (decoding to feature engineering)
- Integrated real-time weather forecast data into the optimisation loop
- Co-supervised a PhD student (with INRIA) on dynamical system identification applied to aircraft performance modelling (2015–2018)

---

## Impact

- Up to **10% fuel savings** during climb phase
- Clients across **10–20 airlines**
- Now deployed on **thousands of aircraft** worldwide via SITA

---

## Stack

Python · scikit-learn · optimisation solvers · real-time weather APIs · Docker · QAR data processing pipelines
