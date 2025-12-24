# Risk Tabular Datasets

This document contains a curated list of publicly available datasets commonly used for credit risk analysis and modeling. Each dataset provides information about credit applicants and their associated risk factors.

## Sources

| Dataset | Link |
|---------|------|
| German Credit Data | https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data |
| Taiwan Credit Risk Dataset | https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients |

All datasets contains the target variable renamed as `target`. A column named as `_is_test` which can be used to split the train/validation/calibration sets from the test partition. The split assignment is random or out-of-time according to the dataset.

More information about dataset and field description and pre-processing can be seen on the respective dataset section.

Any preprocessing scripts used to improve data rediability or for train/test assignment can be side on the `scripts` folder. The final data can be seen on the `data/` folder and the raw dataset before the preprocessing can be seen on the `data/raw` folder.

## Datasets

### German Credit Data
- **Source**: UCI Machine Learning Repository
- **Description**: A widely-used dataset containing attributes and credit risk classifications for 1000 loan applicants. Includes demographic information, credit history, loan details, and other financial characteristics.
- **Link**: https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

##### Fields
XXX

### Taiwan Credit Risk Dataset
- **Source**: UCI Machine Learning Repository
- **Description**: Contains information on default payments, demographic factors, credit data, payment history, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.
- **Link**: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

##### Fields
XXX