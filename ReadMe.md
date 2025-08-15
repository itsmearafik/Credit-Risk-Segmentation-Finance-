# Credit Risk Segmentation

This project analyzes credit risk using unsupervised learning techniques to segment loan applicants into distinct risk categories. It is tailored for financial institutions to improve loan approval strategies. 
The notebook uses the German Credit dataset (Kaggle) with ~1,000 loan applicants labeled as good or bad credit risk— and explores how to segment these customers using clustering to uncover natural groups before even building predictive models. 


## 🔎 Business Problem

Loan defaults impact profitability. Lenders need better segmentation to target low-risk clients and apply differentiated pricing.

## 🔔 Business Questions

- What risk patterns exist among borrowers?
- Can we group applicants based on their credit profile?
- Do younger people request more credit?
- Do customers with low savings show higher risk?
- Correlation heatmaps and bar charts reveal which features separate good vs. bad risk groups more clearly ?


## 📊 Tools & Stack

- Python, Pandas, Scikit-learn
- KMeans Clustering
- Power BI for dashboarding.
- Git & GitHub

## 🌐 Dataset

- [German Bank Customer Segmentation - Kaggle ](https://www.kaggle.com/code/nitishviraktamath/german-bank-customer-segmentation/input)

## 📉 Business Impact

- Enhanced creditworthiness segmentation
- Basis for tiered interest rate policy.
- Provides clear cluster profiles that reveal different credit risk segments.
- Design targeted marketing, to refine supervised risk prediction, or to improve credit policies.

## 🔢 Outputs

- 4 unique customer segments:
  -- Cluster 1: Young people requesting big loans, low savings → risky.
  -- Cluster 2 & 3: Middle-aged customers with medium savings → medium risk.
  -- Cluster 4: Older folks with high savings and short loans → lowest risk.
![](https://github.com/itsmearafik/Credit-Risk-Segmentation-Finance//cluster_analysis.png)
## Key Takeaways

- Identifying clusters can inform loan approval policies or help design targeted offers.
- If you later train a prediction model (e.g. Random Forest), combining cluster membership with other features can improve accuracy.

