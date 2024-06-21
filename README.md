[!header](header.png)
# Health Insurance Charges Analysis

## About
This project aims to analyze factors contributing to health insurance charges in the United States. The analysis is performed using R and includes descriptive statistics, categorical variables examination, correlation analysis, and hypothesis testing. The goal is to identify which variables most significantly impact the amount charged by insurance companies.

## Dataset
The dataset used in this analysis consists of 1,337 rows and 7 columns after cleaning, which involved removing duplicates and handling missing values. The columns in the dataset are:
- `age`: Age of the policyholder (15-64 years)
- `sex`: Gender of the policyholder (male or female)
- `bmi`: Body mass index (15.96 - 53.15 kg/m²)
- `children`: Number of children (0-5)
- `smoker`: Smoking status (yes or no)
- `region`: Region of the policyholder (Southeast, Southwest, Northeast, Northwest)
- `charges`: Insurance charges (US$ 1,122 - US$ 63,770)

## Key Findings
- **Descriptive Statistics**: Policyholders generally have similar ages, BMI, and number of children regardless of smoking status and gender. However, charges are significantly higher for smokers compared to non-smokers, regardless of gender.
- **Categorical Variables**: Distribution of policyholders and charges are relatively similar across different regions.
Proportions of smokers and non-smokers are similar across regions, with a slightly higher proportion of male smokers compared to female smokers.
- **Correlation Analysis**: The analysis shows positive correlations between age, BMI, number of children, and charges. Smoking status has a substantial impact on the charges, with smokers incurring significantly higher charges than non-smokers.

## Analysis Steps
- **Data Cleaning**:
    - Removed duplicates and handled missing values.
    - Checked for the presence of missing values and duplicates.
- **Descriptive Statistics**:
    - Computed means for age, BMI, number of children, and charges based on smoking status and gender.
    - Visualized the differences using bar charts.
- **Categorical Variables Analysis**:
    - Analyzed proportions of policyholders and distributions of charges across regions.
    - Examined proportions of smokers and non-smokers based on region and gender.
- **Correlation and Hypothesis Testing**:
    - Conducted Spearman’s correlation analysis due to the non-normal distribution of some variables.
    - Created a heatmap to visualize the correlation matrix.

## Folder Organization
    .
    ├── README.md                                   <- Top level readme to use this project
    ├── dataset
    │   └── insurance.csv                           <- The dataset
    ├── factors-affecting-insurance-charges.Rproj   <- R project file
    └── notebook
        └── Probabiity-Project.qmd                  <- Quarto notebook

## Installation and Setup
1. Clone the repository
```bash
https://github.com/LingAdeu/factors-affecting-insurance-charges.git
```
2. Install dependencies
```r
install.packages(c("tidyverse", "readr", "dplyr", "ggplot2", "DataExplorer", "gridExtra"))
```
3. Load the dataset and run the analysis script.

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>
