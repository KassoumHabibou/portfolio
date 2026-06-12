---
title: 'Social Protection and Child Stunting in Nigeria: Machine Learning Meets Causal Inference'
summary: This ongoing project combines machine-learning small-area estimates of child stunting with household survey data to evaluate the impact of government cash transfer programs on children's nutrition in Nigeria.
tags:
  - Supervised Learning
date: '2026-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 'District-level (LGA) stunting prevalence estimates in Nigeria from small-area estimation'
  focal_point: Smart

links:

url_code: 'https://github.com/KassoumHabibou'
url_pdf: ''
url_slides: ''
url_video: ''
url_dataset: ''
---

Stunting affects roughly one in three Nigerian children under five, yet reliable district-level data on child nutrition are scarce. This project first leverages **machine learning and Bayesian small-area estimation** techniques to produce stunting prevalence estimates for all 774 Local Government Areas (LGAs) of Nigeria from Demographic and Health Surveys (2008–2024), going far below the level of disaggregation that surveys alone allow.

In a second step, these granular estimates are matched with the **Living Standards Measurement Study (LSMS)** panel surveys to evaluate the impact of government cash transfer programs — rolled out at scale through the **National Social Safety Nets Project (NASSCO, 2016)** — on child stunting, using a **difference-in-differences** design with district and year fixed effects. The analysis also explores whether effects differ when transfers are received by **women versus men**, shedding light on the gender dimension of social protection. This project is carried out using **R** (`fixest`, `tidyverse`) and geospatial tools.
