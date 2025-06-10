
# Torch Deep Learning Model

> This is a deep learning model template for CHAP. It is based on pytorch and can be used to train and predict using deep learning models.  This typically need some configuration to fit the specifics of a dataset.


<img src="https://landportal.org/sites/default/files/2024-03/university_of_oslo_logo.png">

---

## Overview
  
**Target:** `disease_cases`

**Supported Period Type:** `any`

**Developed by:** HISP Centre, University of Oslo

**Contact:** [knutdrand@gmail.com](mailto:knutdrand@gmail.com)

!!! warning Deprecated

    This model might need configuration of hyperparameters in order to work properly.  When the model shows signs of overfitting, reduce 'state_dim' and/or increase 'dropout' and 'weight_decay'.


---

## Covariates

**Required:**

- population

**Allow Additional Covariates:** `True`

---

## User Options


| Name | Type | Default | Description |
| --- | --- | --- | --- |
| additional_covariates | array | ['rainfall', 'mean_temperature'] | ... |
| augmentations | array | [] | ... |
| batch_size | integer | 64 | ... |
| context_length | integer | 12 | ... |
| direct_ar | boolean | False | ... |
| dropout | number | 0.0 | ... |
| embed_dim | integer | 4 | ... |
| embedding_type | string | concat | ... |
| learning_rate | number | 0.001 | ... |
| max_dim | integer | 32 | ... |
| max_epochs | not supported yet... | None | ... |
| n_hidden | integer | 4 | ... |
| n_layers | integer | 1 | ... |
| num_rnn_layers | integer | 1 | ... |
| output_embedding_dim | integer | 0 | ... |
| rnn_type | string | GRU | ... |
| state_dim | integer | 4 | ... |
| use_population | boolean | True | ... |
| weight_decay | number | 1e-06 | ... |

---

## Runtime Environment

**Python:** `: pyenv.yaml`


---
