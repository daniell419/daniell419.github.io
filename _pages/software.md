---
title: "Software"
permalink: /software/
layout: single
author_profile: true
---

# spill_imputation

**Imputation-based Differences-in-Differences estimator with spillovers.**  
Implements an imputation approach that identifies a subset of **never-exposed, never-treated** units to recover untreated counterfactuals and aggregate dynamic effects (ATOTT, ASEU, and optionally ATT(0)) without imposing a pre-specified exposure function. :contentReference[oaicite:0]{index=0}

---

## Installation (R)

```r
# install.packages("devtools")
devtools::install_github("daniell419/spill_imputation")
library(spillimputation)