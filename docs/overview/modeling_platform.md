# Chap Modeling Platform

The Chap modeling platform is a Python framework that handles model orchestration, data pipelines, validation, metrics, and hyperparameter tuning. It automatically calculates evaluation metrics and handles time series correctly via cross-validation. 

The modeling platform supports streamlined integration with the DHIS2 system for accessing health data and disseminating forecasts, but is also fully functional as a stand-alone Python package and commandline tool.

```bash
chap evaluate --model-name https://github.com/dhis2-chap/chap_auto_ewars --dataset-name ISIMIP_dengue_harmonized --dataset-country brazil
```

[View on Github](https://github.com/dhis2-chap/chap-core){ .md-button .md-button--primary } 
