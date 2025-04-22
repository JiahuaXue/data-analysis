# 🛍️ Predicting Customer Response in an E-commerce Marketing Campaign

This project explores the behavioral patterns and characteristics of customers who responded to a marketing campaign, and builds a predictive model to help marketers target more effectively.

## 🧠 Goal
- **Business Question:** What kind of customers are more likely to respond to marketing campaigns?
- **Solution:** Use exploratory data analysis and machine learning to identify important features and predict customer response.

## 🧰 Tools & Techniques
- Python (Pandas, Seaborn, Scikit-learn)
- Random Forest Classifier
- Feature importance visualization
- EDA (distribution plots, correlation heatmaps, spending analysis)

## 📊 Key Findings
- **High-income** and **high-spending** customers are more likely to respond.
- Response rate correlates positively with:
  - Education level
  - Marital status (Single or Together)
  - Spending on Wines and Gold
- **Average income** of respondents is significantly higher.

### 🔍 Feature Importance (Random Forest)
<img src="figures/feature-importance.png" width="500"/>

- Most important features: Income, Recency, Number of Children, etc.
- Model AUC: **0.81**, indicating solid predictive power.

## 🎯 Recommendations
| Customer Type | Key Traits | Strategy |
|---------------|------------|----------|
| A | High-income, high spenders | Target with premium product offers |
| B | Young singles with moderate income | Incentivize via discounts or bundles |
| C | Dormant users with high past spending | Re-engagement emails with exclusive offers |

## 🧪 Bonus: Future Directions
- Build a dashboard to monitor campaign performance (Power BI/Tableau)
- Perform A/B testing on campaign versions to validate targeting improvements

## 📁 Files
- `E-commerce Customer Response Analysis.ipynb`: Full code and visualization
- `dashboard/`: Power BI dashboard (coming soon)
