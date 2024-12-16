# Estimating the Influence of Life Satisfaction

This project investigates factors influencing individuals' life satisfaction using the 2017 Canadian General Social Survey (GSS). Through multiple linear regression and hypothesis testing, we aim to identify and understand how various personal and environmental factors affect people's overall feelings about life.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Findings](#findings)
- [Limitations and Future Work](#limitations-and-future-work)
- [Getting Started](#getting-started)
- [License](#license)

## Introduction
Life satisfaction, a critical measure of well-being, is influenced by various personal and external factors. Using data from the 2017 Canadian General Social Survey, this project analyzes the relationships between life satisfaction and variables such as age, dwelling type, health, education, and employment.

## Data
The study uses data from the **2017 Canadian General Social Survey (GSS)**:
- Survey period: February 2, 2017, to November 30, 2017
- Respondents: 20,000+ Canadians aged 15 and older
- Key variables:
  - Age group
  - Dwelling type (owned/rented)
  - Self-rated health and mental health
  - Education level
  - Employment status and hours worked
  - Marital status
  - Income

Data was cleaned and analyzed using the **R programming language**, with key libraries like `tidyverse` and `ggplot2`.

## Methodology
1. **Linear Regression Analysis**: To identify significant predictors of life satisfaction.
2. **Hypothesis Testing**: Bootstrap methods were used to test relationships, such as the impact of renting versus owning a dwelling.
3. **Visualization**: Data trends and relationships were explored using bar plots, pie charts, and residual plots.

## Results
### Key Findings
- Significant factors affecting life satisfaction:
  - **Age**: 25–34 years and 75+ years showed distinct impacts.
  - **Dwelling**: Renters reported lower satisfaction compared to owners.
  - **Self-rated Health and Mental Health**: Strong correlations with satisfaction levels.
  - **Education**: Higher education levels correlated with better satisfaction.
- Hypothesis testing revealed statistically significant differences between renters and owners regarding self-rated mental health.

### Regression Model
A multiple linear regression model was developed:
Feeling about life = β0 + β1(Age Group) + β2(Dwelling) + β3(Self-rated Health) + β4(Self-rated Mental Health) + β5(Education Level) + error


## Findings
The results underline the importance of addressing health, housing, and education to improve life satisfaction. This research aligns with previous studies emphasizing these factors in determining well-being.

## Limitations and Future Work
- **Data Constraints**: Exclusion of certain populations (e.g., residents of Yukon, Northwest Territories) and reliance on self-reported data.
- **Model Limitations**: Normal Q-Q plots indicate potential violations of model assumptions.
- **Future Directions**:
  - Incorporate additional variables like cultural and regional differences.
  - Use advanced statistical methods (e.g., cross-validation).
  - Conduct follow-up surveys for more granular insights.

## Getting Started
To replicate or extend this analysis, follow these steps:
1. Clone this repository: `git clone https://github.com/XiaoBai-blip/STA304-Paper-3.git`
2. Install required R libraries: `tidyverse`, `ggplot2`, `knitr`
3. Run the provided R scripts to analyze the data and generate visualizations.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

**Author**: Xiao Bai, Yichun Zhang, Hailan Huang  
For more details, see the full report in the repository.

