# 🌍 Global Climate Dynamics: A High-Fidelity Regression Analysis of CO2 Emissions (1990-2023)

<img width="2752" height="1536" alt="unnamed (3)" src="https://github.com/user-attachments/assets/2be2718e-8593-46ee-a211-567bf9ff12d7" />

## Project Overview
This project delivers a robust business analytics report and a high-performing predictive regression model analyzing the key drivers of CO2 emissions across the G20 countries (representing 80% of global emissions) and the sustainable Nordic nations (Sweden, Denmark, Norway, Finland). By analyzing economic, energy, and environmental factors from 1990 to 2023, this work identifies statistically significant predictors of carbon emissions, providing actionable insights for global climate policy development.

--------------------------------------------------------------------------------
## 🚀 Key Results & Impact
The developed Linear Regression (OLS) model successfully captures the dynamics of CO2 emissions, achieving metrics that demonstrate high predictive accuracy and robustness:
<img width="858" height="380" alt="image" src="https://github.com/user-attachments/assets/68a26e0b-ee55-4f38-b605-af6766637b27" />

## 🔍 Key Policy Insights (Coefficient Interpretation)
<img width="879" height="564" alt="image" src="https://github.com/user-attachments/assets/49609b34-41af-49f2-859a-ffaba0d0767f" />


--------------------------------------------------------------------------------
## 🛠 Technical Skills Demonstrated
This project follows the CRISP-DM methodology, showcasing comprehensive data handling, advanced exploratory data analysis (EDA), and sophisticated modeling techniques.

### Data Integrity & Compliance

• Ethical Sourcing: Data was exclusively sourced from highly reliable, authoritative institutions—Our World in Data and the World Bank—to ensure integrity, validity, and trustworthiness, a crucial step often missed in public datasets.

• Privacy Adherence: Strict compliance with ethical guidelines was maintained; all data is aggregated national-level statistics, minimizing privacy concerns (no Personal Identifiable Information/PII).

• Cleaning & Transformation: Performed data joining, cleaned inconsistent country names, filled missing values using techniques like linear interpolation, and applied necessary log transformation and scaling (normalization) to address disparities in feature scales (e.g., GDP).

### Exploratory Data Analysis (EDA) & Feature Engineering
• Correlation Mapping: Conducted extensive correlation analyses across energy, economic, and environmental feature subsets (e.g., coal_co2, oil_co2, gdp, cement_co2).

• Multicollinearity Diagnosis: Identified and managed high correlations suggestive of multicollinearity (e.g., between oil_co2 and gas_co2, and between total_ghg and methane) to refine the feature set prior to modeling.

• Mutual Information Gain: Utilized Mutual Information Gain to identify potential non-linear relationships between features (such as population and oil_co2) and the target variable, which standard correlation analysis fails to detect.

### Modeling & Interpretation
• Regression Modeling: Selected and implemented the Linear Regression algorithm based on evidence of highly correlated, linear relationships between many independent features and the target variable.

• Diagnostic Visualization: Generated visualizations including Actual vs. Predicted plots and detailed scatter plots illustrating the relationships between key predictors (GDP, renewable energy, urbanization) and predicted CO2 emissions.

--------------------------------------------------------------------------------
## 📈 Future Enhancements (Critical Evaluation)
The project includes a reflective evaluation outlining strategies for advanced model improvement, demonstrating critical thinking and readiness for complex data science challenges.

• Advanced Modeling: Future work involves exploring non-linear modeling techniques, such as XGBoost or Random Forests, to potentially capture more complex patterns and achieve higher predictive accuracy.

• Policy Variables: Recommended enhancement includes augmenting the dataset with detailed, policy-related variables (e.g., carbon taxes, renewable energy subsidies) to gain deeper causal insights into policy effectiveness.

• Dimensionality Reduction: Proposed use of Principal Component Analysis (PCA) to address residual multicollinearity, improve model interpretability, and reduce dimensionality.

• Feature Engineering: Suggested creation of complex features like energy efficiency (energy consumption per unit of GDP) and carbon intensity (CO2 emissions per unit of energy).

--------------------------------------------------------------------------------
## 📚 Repository Structure and Sources
The data for this study was augmented using information on renewable energy, urbanization, and agricultural value addition to allow for a comprehensive analysis.

• Code & Datasets: Available here: https://github.com/AshishSiwach/BEMM457_Coursework2.git

• Data Sources: Our World in Data, World Bank (WDI).
