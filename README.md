# Comparative Analysis of Classification Models for Predicting Term Deposit Subscriptions

## Introduction  
This project investigates the factors influencing the subscription of term deposits (`yes/no`) using data from a Portuguese banking institution's directed marketing campaigns. These campaigns, conducted via phone calls, targeted potential clients to promote bank term deposits. The dataset contains 10,000 records from 17 campaigns conducted between May 2008 and November 2010, capturing economic, demographic, and campaign-specific details. This study was conducted as part of the University of Glasgow MSc Data Analytics program (2023–24) for the course *Data Mining and Machine Learning*, using a dataset provided by the course instructors.

The study aimed to predict term deposit subscriptions using several classification models, including **KNN**, **LDA/QDA**, **SVM**, and **Tree-based methods**. 

---

## Project Objectives  

The key objectives of this study include:  
1. **Data Preparation and Cleaning**: Ensuring completeness and consistency in the dataset.  
2. **Exploratory Data Analysis (EDA)**: Visualizing and summarizing key variables to uncover trends and patterns.  
3. **Model Comparison**: Evaluating multiple classification models (KNN, LDA/QDA, SVM, and Random Forest) for predictive performance.  
4. **Feature Importance Analysis**: Identifying the most influential factors impacting term deposit subscriptions.  
5. **Insights and Recommendations**: Providing actionable insights based on model results and economic/demographic patterns.  

---

## Tools and Technologies  

- **Languages**: R  
- **Techniques**: Predictive Modeling, Feature Importance Analysis, Data Visualization, Model Comparison  
- **Version Control**: GitHub (for code and documentation)  

### Libraries Used  
The following R libraries were utilized for this project:  
- `gmodels`  
- `dplyr`  
- `skimr`  
- `gt`  
- `ggplot2`  
- `GGally`  
- `gridExtra`  
- `class`  
- `MASS`  
- `caret`  
- `e1071`  
- `ROCR`  
- `corrplot`  
- `pROC`  
- `rpart`  
- `randomForest`  
- `rpart.plot`  
- `knitr`  

---

## Files and Structure  

- **R Folder**:  
- `term-deposits-analysis.qmd`: R script for data preprocessing, exploratory data analysis, and comparative model analysis.  
- `term-deposits-report.pdf`: Final project report summarizing analysis, insights, and recommendations.  
  
---

## Insights  

The **Random Forest model** demonstrated the highest predictive accuracy due to its ensemble approach, which combines multiple decision trees to reduce variance and improve robustness against overfitting. Key insights include:   Key insights include:  

- **Economic Indicators**: Variables such as `number of employees` and `three-month Euribor rate` were critical predictors of subscription.  
- **Demographic Factors**: Attributes like `age`, `job`, and `education` played significant roles in customer decisions.  

These findings emphasize the influence of both economic conditions and personal demographics on subscription behavior, suggesting the value of targeted marketing strategies.  

---

## Conclusion  

This project demonstrates the effectiveness of the **Random Forest model** in predicting term deposit subscriptions. Its ability to handle diverse variable scales without extensive preprocessing made it an ideal choice for this dataset, which includes a mix of economic and demographic factors. These insights can assist financial institutions in optimizing marketing campaigns and refining customer targeting strategies.  



