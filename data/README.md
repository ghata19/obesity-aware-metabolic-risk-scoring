# Data

The raw datasets used in this project are **not included in the repository**.

This is intentional to keep the repository lightweight and avoid committing raw dataset files.

## Datasets Used

### 1. UCI Obesity Dataset

Used for the first stage of the project:

- 2,111 observations
- 17 features
- 7 obesity-related target classes
- Demographic, anthropometric, lifestyle, and behavioral variables

The dataset is used to train the obesity classification model.

### 2. NHANES 2013–2014

Used for the metabolic syndrome modeling stage.

The project integrates relevant NHANES demographic, anthropometric, laboratory, and clinical variables to construct a metabolic syndrome target based on five clinical criteria.

The final modeling dataset contains 2,422 complete-panel subjects.

## Local Setup

After obtaining the datasets, place the required raw files in this `data/` directory.

Raw `.csv`, `.xlsx`, `.xls`, and `.zip` files are excluded from Git tracking through the repository's `.gitignore`.

See the main project README for the overall methodology and modeling pipeline.
