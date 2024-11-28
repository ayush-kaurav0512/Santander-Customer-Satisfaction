# Santander-Customer-Satisfaction

From frontline support teams to C-suites, customer satisfaction is a key measure of success. Unhappy customers don't stick around. What's more, unhappy customers rarely voice their dissatisfaction before leaving.
Santander Bank is asking Kagglers to help them identify dissatisfied customers early in their relationship. Doing so would allow Santander to take proactive steps to improve a customer's happiness before it's too late.
In this competition, you'll work with hundreds of anonymized features to predict if a customer is satisfied or dissatisfied with their banking experience.

## Dataset Description

You are provided with an anonymized dataset containing a large number of numeric variables. The "TARGET" column is the variable to predict. It equals one for unsatisfied customers and 0 for satisfied customers.

The task is to predict the probability that each customer in the test set is an unsatisfied customer.

File descriptions

train.csv - the training set including the target.

test.csv - the test set without the target.

sample_submission.csv - a sample submission file in the correct format.

## Task Performed 

### Task Instructions for Decision Tree Analysis and Kaggle Submission

This task involves implementing decision tree models to predict customer satisfaction, performing data analysis, and documenting results using Kaggle submissions. Follow the detailed steps below:

---

#### **1. Kaggle Submissions**
- Train multiple decision tree models with varying configurations to predict the target variable.
- **Steps:**
  1. Prepare the training and test datasets as per Kaggle's competition guidelines.
  2. Train decision tree models and generate predictions for the test set.
  3. Submit test predictions to Kaggle and record scores and rankings.
- **Deliverables:**
  - Screenshots of Kaggle scores and rankings.
  - Incorporate these screenshots into a detailed report.
  - Include the scores/rankings in a summary table.

---

#### **2. Exploratory Data Analysis (EDA)**
- Conduct EDA to identify relevant and irrelevant features.
- **Steps:**
  1. Analyze feature distributions, correlations, and their impact on the target variable.
  2. Identify three irrelevant variables and provide justifications for why they do not contribute to the prediction.
  3. Identify three relevant variables critical for predicting unsatisfied customers and justify their importance.
- **Deliverables:**
  - Visualizations or statistical analysis to support findings.
  - Documented insights on feature relevance in the report.

---

#### **3. Parameter Tuning for Decision Trees**
- Experiment with at least three different parameter configurations.
- **Steps:**
  1. Tune parameters such as:
     - **Depth of the tree**
     - **Splitting criterion** (e.g., Gini vs. entropy)
     - **Maximum number of leaf nodes**
  2. For each parameter configuration:
     - Train the decision tree model.
     - Record the Kaggle scores.
  3. Use Python code screenshots to explain parameter changes.
- **Deliverables:**
  - Compare model performance using an Excel table.
  - Highlight the best-performing configuration and justify why it works best based on Kaggle scores and model behavior.

---

#### **4. Challenges in Machine Learning for This Problem**
- Analyze why the customer satisfaction prediction problem is challenging.
- **Points to consider:**
  - High-dimensional feature space.
  - Class imbalance issues (e.g., fewer unsatisfied customers).
  - Irrelevant or noisy features in the dataset.
  - Trade-offs between model complexity and overfitting/underfitting.
Deliverables:
  - A concise explanation in the report.
  - Insights into specific challenges faced during model development and data preprocessing.

##Kaggle Url:- 

https://www.kaggle.com/c/santander-customer-satisfaction/overview
