# War & Happiness: Regression Analysis Using the World Happiness Report

This project was completed as part of the PSTAT 100 course at UCSB in Summer 2025. Our objective was to explore how war and conflict influence national happiness by analyzing data from the **World Happiness Report (2005–2023)** and applying predictive modeling techniques.

---

## 📊 Objective

To investigate how war and conflict impact national happiness levels over time using data from the **World Happiness Report**. The primary outcome variable, the **Life Ladder** (happiness score), was analyzed in relation to key socioeconomic and governance indicators.

---

## 🔍 Dataset

We used the **2023 World Happiness Report**, which includes data across multiple years (2005–2023) and features the following variables:

- Life Ladder (Happiness Score)
- Log GDP per capita
- Social Support
- Healthy Life Expectancy
- Freedom to Make Life Choices
- Generosity
- Perceptions of Corruption

Countries were tagged as being involved in war or not during specific time periods to assess differences in trends.

---

## ⚙️ Methods

- **Data Wrangling:** Filtered and transformed data using `dplyr`, grouped countries by conflict status and year.
- **Regression Modeling:** Built multiple linear regression models using `lm()` to predict happiness scores from economic and social indicators.
- **Model Evaluation:** Examined residual plots, R² values, and multicollinearity through correlation analysis.
- **Visualization:** Used `ggplot2`, `broom`, and `corrplot` to produce plots for interpretation and presentation.
- **Interpretation:** Focused on the real-world implications of model results, particularly in regions affected by conflict.

---

## 🧠 My Role (Anush Harish)

As part of this collaborative project, I led the data science workflow for Tasks 4–6:

- **Data Wrangling & Cleaning:** Used `dplyr` to transform and filter real-world survey data, handled missing values, and created indicators to track imputation rates across predictors.
- **Exploratory Data Analysis (EDA):** Identified distribution patterns and group-level differences across housing types and poverty metrics using summary statistics and grouped aggregations.
- **Statistical Modeling:** Built and interpreted multiple **linear regression models** using `lm()` to quantify the influence of economic and social factors on national happiness.
- **Diagnostic Evaluation:** Assessed model validity through **residual analysis**, checked for outliers and multicollinearity using **correlation matrices**, and evaluated potential biases in the modeling process.
- **Visualization:** Generated **publication-ready plots** using `ggplot2`, `broom`, and `corrplot`, including residual plots, confidence intervals, and heatmaps.
- **Communication:** Translated statistical findings into non-technical insights in both written report form and slide presentations, tailored for stakeholders with varying levels of data fluency.

---



## 🚀 Tools & Technologies

- **Languages:** R
- **Libraries:** tidyverse, ggplot2, broom, corrplot
- **Workflow:** RStudio, markdown-based reporting, collaborative Google Slides for presentation

---

## ✅ Key Takeaways

This project demonstrates how real-world socio-economic data can be analyzed using statistical and machine learning foundations to derive meaningful insights. It showcases my ability to work with real datasets, communicate findings clearly, and apply technical methods — all of which are crucial for success in AI/ML internships.


