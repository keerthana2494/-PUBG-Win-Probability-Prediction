# -PUBG-Win-Probability-Prediction
# **1. Introduction**
- The objective of this project is to analyze the PUBG match dataset to understand key factors that influence the win probability and build a predictive model to estimate the likelihood of winning based on various in-game features.

# **2. Data Analysis**
**2.1 Data Description**
- The dataset consists of multiple features representing player performance metrics such as kills, damage dealt, assists, etc.
- Data Shape: (201 rows, 26 columns)
- Key features include: kills, damageDealt, walkDistance, weaponsAcquired, boosts, and winPlacePerc.

**2.2 Data Cleaning**

- Handled missing values using mean/mode imputation techniques.

- Removed outliers based on interquartile range (IQR).

**2.3 Data Exploration**

- Conducted univariate and bivariate analysis.

- Visualizations included histograms, box plots, and correlation heatmaps.

- Key insights:

- Positive correlation between kills and win probability.

- Significant impact of survival time and damage dealt on winning.

# **3. Predictive Model**
**3.1 Feature Selection**

- Selected key features based on correlation analysis and feature importance scores.

- Features: kills, damageDealt, walkDistance, weaponsAcquired, and boosts.

**3.2 Model Building**

- Implemented multiple models: Linear Regression, Decision Tree, Random Forest.

- Random Forest outperformed with accuracy of 85%.

**3.3 Model Evaluation**

- Evaluated using MAE, MSE, and R-squared metrics.

- Random Forest had the best performance with R-squared value of 0.85.

# **4. Important Factors Affecting Win Probability**
- kills and damageDealt have the highest impact on win probability.

- Strategic movement (walkDistance) and resource management (boosts, weaponsAcquired) are significant.

# **5. Conclusion**
- The analysis highlights key factors influencing win probability in PUBG.

- The Random Forest model accurately predicts the win probability, providing actionable insights for improving gameplay strategy. 
