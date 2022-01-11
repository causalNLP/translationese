
This repo stores codes for causal analysis on machine translation direction.

## Step 1. Download the Data
- Our CausalMT 2.0 corpus can be downloaded from [this Google drive folder](https://drive.google.com/drive/folders/19yKCbpOLt6uMDcbWD77vKH3pyPBIAAw2?usp=sharing).

File structure
```
- causalMT2.0
  - general_data
  - synthetic_simplification_data
  - topic_aligned_subset
```
For each subfolder (e.g., `general_data`, `synthetic_simplification_data`, `topic_aligned_subset`), there are 10 data collection directions (= 5 language pairs * 2 directions per pair) in total:
```
    - de-en
      - train.de
      - train.en
      - dev.de
      - dev.en
      - test.de
      - test.en
      - train.nobpe.de
      - train.nobpe.en
      - dev.nobpe.de
      - dev.nobpe.en
      - test.nobpe.de
      - test.nobpe.en
    - de-fr
      - ...
    - en-de
      - ...
    - en-es
      - ...
    - en-fr
      - ...
    - es-en
      - ...
    - es-fr
      - ...
    - fr-de
      - ...
    - fr-en
      - ...
    - fr-es
      - ...
```
