---
title: "Software"
permalink: /software/
layout: single
author_profile: true
---

- # 1) spill_imputation
**Imputation-based Differences-in-Differences estimator for spillovers.**  
Implements an imputation approach that uses a subset of **never-exposed, untreated** units to recover untreated counterfactuals and aggregate dynamic effects (ATOT and ASEU) without imposing a pre-specified exposure function.

## 📦 Repository

**GitHub:** [daniell419/spill_imputation](https://github.com/daniell419/spill_imputation)

---

## Installation (R)

```r
# install.packages("devtools")
devtools::install_github("daniell419/spill_imputation")
library(spillimputation)
```