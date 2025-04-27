# University Analysis and Evaluation

## Understanding Factors Affecting University Characteristics and Performance

### Overview
This project explores the use of educational data mining (EDM) and machine learning techniques to analyze and predict university performance metrics, specifically graduation and retention rates. By leveraging institutional data from the **Integrated Postsecondary Education Data System (IPEDS)**, the study identifies key factors influencing these outcomes and provides actionable insights for policymakers and university administrators.

---

### Objectives
1. **Exploratory Data Analysis**: Uncover patterns and relationships within university attributes.
2. **Data Preprocessing**: Implement cleaning, transformation, and feature engineering techniques.
3. **Predictive Modelling**: Utilize machine learning algorithms to predict graduation and retention rates.
4. **Feature Importance Analysis**: Use SHAP (Shapley Additive Explanations) to interpret model outputs.
5. **Policy Recommendations**: Propose actionable strategies to improve university performance.

---

### Methodology
This study employs the **Knowledge Discovery in Databases (KDD)** methodology, involving the following steps:
- **Data Selection**: Institutional data from IPEDS focusing on 4-year undergraduate programs.
- **Data Cleaning and Transformation**: Address missing values, normalize distributions, and standardize features.
- **Feature Engineering**: Create and select impactful variables using statistical techniques like VIF.
- **Machine Learning Models**: Apply the following algorithms:
  - **Linear Regression**
  - **Support Vector Regression (SVR)**
  - **Decision Trees**
  - **Random Forest**
  - **XGBoost**
- **Hyperparameter Tuning**: Perform grid search with k-fold cross-validation.
- **Evaluation Metrics**: Assess models using R-Square, RMSE, and MAE.
- **Interpretability**: Use SHAP to highlight key predictors for graduation and retention rates.

---

### Results
- **Graduation Rates**:
  - Best Model: Linear Regression with R-Square = **89.19%**, RMSE = **6.63**, MAE = **4.49**.
  - Key Predictors: Funding and financial support for students.
- **Retention Rates**:
  - Best Model: Optimized SVR with R-Square = **73.5%**, RMSE = **5.93**, MAE = **4.48**.
  - Key Predictors: Tuition fees, test scores, and financial assistance.
- **Insights**:
  - Increased funding, financial aid, and student services are associated with higher graduation rates.
  - High tuition correlates with lower retention rates, while strong test scores and financial support improve retention.

---

### Tools and Technologies
- **Programming**: Python (Scikit-learn, SHAP, Matplotlib, Pandas, NumPy)
- **Data Sources**: IPEDS-NCES datasets
- **Statistical Analysis**: VIF, correlation analysis, and feature scaling
- **Visualization**: Tableau, SHAP plots and correlation matrices

---

## Tableau Dashboard
Explore the interactive dashboard on [Tableau Public](https://public.tableau.com/views/UniversityPerformanceandAnalysis/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

---

### Key Contributions
- Introduced interpretability into machine learning models for higher education.
- Highlighted actionable insights for university administrators and policymakers.
- Enhanced understanding of factors influencing key performance metrics in higher education.

---

### Limitations and Future Work
#### Limitations:
- Limited to institutional-level data; student-level insights were not explored.
- Focused on U.S. universities; results may not generalize globally.

#### Future Work:
- Incorporate student-level behavioral and demographic data.
- Expand analysis to global datasets for comparative insights.
- Explore deep learning models for improved prediction accuracy.

---


### Author
**Clement Appeadu**  
MSc Data Science, University of South Wales  
[LinkedIn](https://www.linkedin.com/in/clement-appeadu-9b6a2b148)  

---

### Acknowledgments
Special thanks to my supervisor, Nicholas Andrews, and the academic staff at the University of South Wales for their guidance and support. Gratitude also to my family for their unwavering encouragement.

---



