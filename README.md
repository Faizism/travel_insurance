<h1> Travel Insurance Classification </h1>

## 1. Project Overview
This project aims to build a machine learning model to classify whether a customer will file a travel insurance claim. By analyzing historical customer data, the project seeks to identify key patterns and indicators associated with insurance claims. This will enable TravelSafe Insurance to optimize their reinsurance strategy and better manage risks.

Key Objectives:
- Objective 1: Understand customer behavior and attributes linked to insurance claims.
- Objective 2: Develop a predictive model to classify high-risk policies for targeted reinsurance efforts.

Challenges Addressed:
- High reinsurance costs due to a "one-size-fits-all" approach, leading to inefficiencies and uncovered claims.
- Identification of high-risk policies to minimize uncovered claim risks and unnecessary reinsurance costs.

Evaluation Metrics:
- **Business Metric**: Reinsurance Efficiency Ratio (RER)
- **Model Metric**: ROC-AUC (Receiver Operating Characteristic - Area Under Curve)

Success Criteria:
- Achieve an ROC-AUC score greater than 0.8, ensuring reliable model performance for operational use.
  
## 2. Data Sources
- [Dataset 1](https://intip.in/travelinsurancedataset) - Description of dataset (e.g., Historical Travel Insurance Customer)

## 3. Technologies Used
Version Control: Git
- Programming Language: Python (Pandas, NumPy, Scikit-learn)
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn (Logistic Regression, Decision Trees, etc.)
- Version Control: Git
- Development Environment: Jupyter Notebook


## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks.
│   └── raw            <- Trained and serialized models, model predictions, or model summaries
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as PDF and PPT
│
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insights
- Significant patterns in customer demographics and travel preferences influence insurance claims.
- Customers traveling to high-risk destinations or purchasing specific insurance products are more likely to file claims.

### 5.2 Actionable Recommendations
- Implement targeted marketing strategies for high-risk destinations and customer groups.
- Develop reinsurance strategies focused on high-risk policies to reduce unnecessary costs while ensuring adequate coverage.

## 6. Contact
- Name: Muhammad Fa'iz Ismail
- Email: ismail1.faiz1@gmail.com
- Linkedin: https://www.linkedin.com/in/m-faiz-ismail/
