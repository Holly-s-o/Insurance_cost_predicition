# Insurance Cost Predicition
This project explores and analyzes insurance cost data to understand the factors that influence individual medical charges.
The analysis focuses on identifying relationships among age, gender, BMI, region, smoking habits, and number of dependents, and how these variables collectively affect insurance pricing and cost behavior. By performing detailed exploratory data analysis (EDA), the project provides insights that could guide pricing strategies, risk assessment, and customer segmentation within the insurance industry.

## Objectives

The main goals of this project are to:

* Understand the distribution and structure of the insurance dataset.
* Identify key demographic and behavioral factors influencing insurance costs.
* Analyze correlations between independent features (age, BMI, smoking, etc.) and insurance charges.
* Highlight cost disparities across gender, regions, and health-related variables.
* Provide data-driven recommendations for fair and efficient premium pricing.

## Tools & Technologies

| Category           | Tools Used                      |
| ------------------ | ------------------------------- |
| Programming        | Python                          |
| Data Handling      | Pandas, NumPy                   |
| Data Visualization | Matplotlib, Seaborn             |
| Environment        | Jupyter Notebook                |
| Analysis Type      | Exploratory Data Analysis (EDA) |

## Dataset Description

The dataset consists of health and demographic details of insurance policyholders, including:

| Feature      | Description                                                   |
| ------------ | ------------------------------------------------------------- |
| **age**      | Age of the primary beneficiary                                |
| **sex**      | Gender of the individual (male/female)                        |
| **bmi**      | Body Mass Index (indicator of obesity)                        |
| **children** | Number of dependents covered by insurance                     |
| **smoker**   | Smoking status of the individual (yes/no)                     |
| **region**   | Residential area (northeast, northwest, southeast, southwest) |
| **charges**  | Medical insurance costs billed to the individual              |

The dataset serves as the foundation for exploring cost variations based on health and lifestyle characteristics.

## Exploratory Data Analysis (EDA)

The EDA process involved:

* Data Cleaning: Checked for null values, duplicates, and data-type consistency.
* Univariate Analysis: Examined the distribution of age, BMI, and charges.
* Bivariate Analysis: Compared relationships between independent features and insurance costs.
* Correlation Analysis: Used a heatmap to visualize variable correlations.
* Categorical Analysis: Compared cost differences by gender, smoker status, and region.

## Key Insights

* Age: Insurance cost increases with age — older individuals tend to pay significantly higher charges.
* BMI: Higher BMI (above 30) strongly correlates with increased insurance costs, indicating obesity-related health risks.
* Smoking: Smokers pay substantially higher insurance charges — often 2–3 times more than non-smokers.
* Gender: No major cost disparity was observed between male and female policyholders.
* Children: Number of dependents has a minor impact on charges.
* Region: Minimal difference across regions, but slight variations may exist in the southeast and southwest zones.

## Recommendations

1. Smoking Risk Adjustment: Introduce premium adjustments or health-based incentive programs for smokers.
2. Wellness Programs: Promote weight management and preventive healthcare for individuals with high BMI.
3. Age-Based Risk Pooling: Review pricing strategies to ensure fairness across age brackets.
4. Data-Driven Policy Design: Use demographic and health insights to design targeted insurance packages.


## Tech Stack Summary

* Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn
* Environment: Jupyter Notebook
* Analysis Type: Exploratory Data Analysis (EDA)

## Author

**Holiness Segun-Olufemi**
Public Policy Professional | Data Scientist | Researcher
