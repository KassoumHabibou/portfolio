---
title: Analysing Senegal Census Data
summary: This project aims to use Senegal census data to understand population dynamics through spatial data analysis.
tags:
  - Supervised Learning
date: '2023-10-27'
# T00:00:00Z
# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Mappitall
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/Abson-dev/Analysing-Senegal-Census-Data'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

The **Analyzing Senegal Census Data** project is a part of understanding how poverty changes over time in Dakar, Senegal. The goal is to figure out what mainly causes poverty in Senegal using spatial data analysis.

In this study, we used data from the two General Population Censuses (RGPH) of Senegal conducted in 2002 and 2013. After carefully cleaning the data, we calculated various characteristics at the district level, such as the average age of household heads, average years of education, and number of children per household and then conducted descriptive statistics on them. We also calculated the Multidimensional Poverty Index [(MPI)](https://www.worldbank.org/en/topic/poverty/brief/multidimensional-poverty-measure) using household-level data. Initially, we computed each dimension of the MPI (health, education, and standard of living) at the household level. This index was then aggregated at the district level (specific to each census) before proceeding to spatial analysis.

We run several models, including the *spatial lag model*, *spatial error models* and *geographically weighted regression*. Overall, we found that characteristics of the household head (such as years of education, ethnicity, age, gender, and employment status) are the main factors explaining poverty in Dakar. District composition factors such as the number of individuals under fifteen, population density and settlement index also play an important role in explaining poverty.

This work was conducted in collaboration with [Aboubacar HEMA](https://hema.quarto.pub/aboubacar-hema/) and was performed using **R** as the statistical tool. You can find 👉 [here](https://github.com/Abson-dev/Analysing-Senegal-Census-Data) the replication codes of this study.
