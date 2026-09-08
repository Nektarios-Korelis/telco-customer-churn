\# Telco Customer Churn Prediction



A machine learning project that analyzes customer churn in a telecommunications company and builds classification models to predict whether a customer is likely to leave.



\##  Project Overview



This project explores customer characteristics, identifies factors associated with churn, and compares several machine learning models.



The project includes:



\* Data cleaning and preprocessing

\* Exploratory Data Analysis (EDA)

\* SQLite database integration

\* Machine learning model training

\* Hyperparameter tuning

\* Model evaluation

\* SHAP model interpretation



\##  Dataset



The project uses the \*\*Telco Customer Churn\*\* dataset.



\* \*\*Rows:\*\* 7,043

\* \*\*Columns:\*\* 21

\* \*\*Target:\*\* `Churn`

\* \*\*Overall churn:\*\* 26.54%



\##  Machine Learning



The following models were evaluated:



\* Logistic Regression

\* K-Nearest Neighbors (KNN)

\* Support Vector Classifier (SVC)

\* Decision Tree

\* Random Forest

\* Gradient Boosting



Gradient Boosting and Random Forest were tuned using \*\*5-fold cross-validation\*\* with F1-score as the optimization metric.



\##  Results



| Model                 |   ROC-AUC |

| --------------------- | --------: |

| \*\*Gradient Boosting\*\* | \*\*0.843\*\* |

| Logistic Regression   |     0.842 |

| Random Forest         |     0.838 |

| Decision Tree         |     0.830 |

| KNN                   |     0.824 |

| SVC                   |     0.790 |



\### Gradient Boosting



\* \*\*Accuracy:\*\* 80%

\* \*\*Precision:\*\* 66%

\* \*\*Recall:\*\* 52%

\* \*\*F1-score:\*\* 59%



\##  Key Insights



\* Month-to-month customers have substantially higher churn.

\* Fiber optic customers show relatively high churn.

\* Electronic check customers have higher churn.

\* Longer-term contracts are associated with much lower churn.

\* Shorter-tenure customers tend to have higher churn risk.



\## 🛠️ Technologies



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-learn

\* SHAP

\* SQLite

\* Jupyter Notebook





\##  How to Run



Install the required libraries:



```bash

pip install -r requirements.txt

```



Open the notebook:



```bash

jupyter notebook "Project 2.ipynb"

```



Make sure the dataset is located in the `data/` directory.



\## Author



Nektarios Korelis



