
# CHAP-EWARS Model

> Modified version of the World Health Organization (WHO) EWARS model. EWARS is a Bayesian hierarchical model implemented with the INLA library.


<img src="https://landportal.org/sites/default/files/2024-03/university_of_oslo_logo.png">

---

## Overview
  
**Target:** `disease_cases`

**Supported Period Type:** `any`

**Developed by:** HISP Centre, University of Oslo

**Contact:** [knut.rand@dhis2.org](mailto:knut.rand@dhis2.org)

!!! warning Deprecated

    None

---

## Covariates

**Required:**

- population

**Allow Additional Covariates:** `True`

---

## User Options


| Name | Type | Default | Description |
| --- | --- | --- | --- |
| n_lags | integer | 3 | ... |
| precision | number | 0.01 | ... |

---

## Runtime Environment

**Docker:** `: {'image': 'ghcr.io/dhis2-chap/docker_r_inla:master'}`


---
