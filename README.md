# Smoking Cessation Study

## Project Overview
This project analyzes baseline variables as predictors of smoking abstinence in adults with major depressive disorder (MDD) and examines potential moderating effects of these variables on the efficacy of two treatments: **Behavioral Activation (BA)** and **Varenicline (Var)**. By exploring interactions between baseline characteristics and treatment types, the study aims to identify which factors impact treatment success and how these insights can inform personalized smoking cessation strategies.

## Data
The dataset contains various demographic and clinical variables related to smoking habits, nicotine dependence, and treatment outcomes.
Due to data privacy concerns, the raw data files are not included in this repository. 

## Analysis Methods
The analysis consists of several steps:
1. **Exploratory Data Analysis (EDA)**: Visualizing distributions of key variables, including age, FTCD score, and daily cigarette consumption, to understand the sample characteristics.
2. **Variable Selection**: Using LASSO regression to identify important baseline predictors of smoking abstinence.
3. **Interaction Analysis**: Examining potential interactions between baseline variables (e.g., `NMR`, `ftcd_score`) and treatment types (BA and Var) to assess how these interactions influence abstinence outcomes.
4. **Model Evaluation**: Using ROC curves and AUC metrics to evaluate model performance in predicting abstinence.

## Key Findings
- **Baseline Predictors**: Age, nicotine dependence (FTCD score), and Non-Hispanic White status were significant predictors of smoking abstinence.
- **Interaction Effects**: The Nicotine Metabolism Rate (NMR) moderates the effect of Varenicline, with high NMR levels enhancing treatment efficacy.
- **Implications for Personalized Treatment**: Findings suggest that baseline characteristics, particularly nicotine metabolism, could inform personalized smoking cessation interventions, especially in adults with MDD.

## Files and Structure
Report/EDA_report.Rmd: RMarkdown containing exploratory analysis and interpretations.
Report/EDA_report.pdf: PDF version of the exploratory analysis with code appendix.
