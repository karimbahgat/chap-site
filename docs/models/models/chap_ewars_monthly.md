
# Monthly CHAP-EWARS model

> Modified version of the World Health Organization (WHO) EWARS model. EWARS is a Bayesian hierarchical model implemented with the INLA library.


<img src="https://landportal.org/sites/default/files/2024-03/university_of_oslo_logo.png">

---

## Overview
  
**Target:** `disease_cases`

**Supported Period Type:** `month`

**Developed by:** HISP Centre, University of Oslo

**Contact:** [knut.rand@dhis2.org](mailto:knut.rand@dhis2.org)

!!! warning Deprecated

    Deprecated, replaced by Flexible EWARS Model

---

## Covariates

**Required:**

- rainfall

- mean_temperature

- population

**Allow Additional Covariates:** `False`

---

## User Options

This model does not have configurable user options.

---

## Runtime Environment

**Docker:** `: {'image': 'ivargr/r_inla:latest'}`


---
