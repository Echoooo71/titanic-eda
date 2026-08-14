# Titanic Survival Exploratory Data Analysis

## Overview
This project analyzes the Titanic passenger dataset and explores factors associated with passenger survival.

## Research Questions
- What is the overall survival rate?
- How are sex and survival related?
- How are passenger class and survival related?
- How are age, fare, and family size related to survival?

## Dataset
The dataset contains information about 891 Titanic passengers, including sex, age, passenger class, fare, family members, and survival status.

Source: https://github.com/datasciencedojo/datasets/blob/master/titanic.csv

## Analysis
The notebook includes:

- Overall survival statistics
- Survival analysis by sex
- Survival analysis by passenger class
- Age-group survival analysis
- Fare analysis
- Family-size analysis
- Data visualizations with Matplotlib

## Key Findings
- The overall survival rate was 38.38%.
- Female passengers had a substantially higher survival rate than male passengers.
- First-class passengers had the highest survival rate.
- Age, fare, and family size were associated with survival, but the analysis shows association rather than causation.

## Notes
`Age` contains missing values. Age-related analysis uses passengers with known age values, so conclusions should be interpreted within that subset.

## Requirements
Install the dependencies with:

```bash
pip install -r requirements.txt
```

Then open and run `titanic.ipynb` in Jupyter Notebook.
