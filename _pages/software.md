---
title: "Software"
permalink: /software/
layout: single
author_profile: true
---

# spill_imputation

**Imputation-based Differences-in-Differences estimator for spillovers.**  
Implements an imputation approach that uses a subset of **never-exposed, untreated** units to recover untreated counterfactuals and aggregate dynamic effects (ATOT, and ASEU) without imposing a pre-specified exposure function.

---

## Installation (R)

```r
# install.packages("devtools")
devtools::install_github("daniell419/spill_imputation")
library(spillimputation)
```