# Credit-Card-Default-Prediction-Project
![image](https://user-images.githubusercontent.com/114734243/227272617-c0dc1c89-748e-44e9-a694-476ec37f8616.png)

# **Project Summary :**

Today’s world credit cards have become a lifeline to a lot of people so banks provide us with credit cards
A credit card is a type of payment card in which charges are made against a line of credit instead of the account holder’s cash
deposit . when someone uses a credit card to make purchase , that person’s account accrues a balance that must be paid off
each month
Now we know the most common issue there is in providing these kinds of deals are people not being able to pay the bills . theses
people are what we call ”DEFAULTERS”
The Credit Card Default Database is the most comprehensive classified with Unbalanced dataset ,data set of Customer credit
card default payments in Taiwan , which provides information on domestic around the Taiwan from 6months in 2005 For this
a widespread information is available, including the payment history and bill _Amount, paid amount, nature of the target i.e
Defaulters etc. This project main objective is Perform ‘Exploratory Data Analysis’AND applying Machine learning algorithms
aimed at predicting the case of customers default payments in Taiwan accuracy of Defaulters on dataset '``.Credit card
Defaulter prediction
Our Project is to Investigate patterns and explanations in the context and convey the results in a dynamic and visual manner.

![image](https://user-images.githubusercontent.com/114734243/227273179-a295696a-f50e-4ff8-ab5a-ed5f16fecf11.png)

## **Features Description**
We have records of 30000 customers. Below are the description of all features:

* **ID:** ID of each client*

* **LIMIT_BAL:**  Amount of given credit in NT dollars (includes individual and family/supplementary credit)*

* **SEX:** Gender (1 = male, 2 = female)*

* **EDUCATION:** (1 = graduate school, 2 = university, 3 = high school, 0,4,5,6 = others)*

* **MARRIAGE:** Marital status (0 = others, 1 = married, 2 = single, 3 = others)*

* **AGE:** Age in years*

 **History of past payment**

**We tracked the past monthly payment records from April to September, 2005.The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.**

**PAY_0:** Repayment status in September, 2005 (scale same as above)

**PAY_2:** Repayment status in August, 2005 (scale same as above)

**PAY_3:** Repayment status in July, 2005 (scale same as above)

**PAY_4:** Repayment status in June, 2005 (scale same as above)

**PAY_5:** Repayment status in May, 2005 (scale same as above)

**PAY_6:** Repayment status in April, 2005 (scale same as above)

**Amount of bill statement (NT dollar)**

**BILL_AMT1:** Amount of bill statement in September, 2005 (NT dollar)

**BILL_AMT2:** Amount of bill statement in August, 2005 (NT dollar)

**BILL_AMT3:** Amount of bill statement in July, 2005 (NT dollar)

**BILL_AMT4:** Amount of bill statement in June, 2005 (NT dollar)

**BILL_AMT5:** Amount of bill statement in May, 2005 (NT dollar)

**BILL_AMT6:** Amount of bill statement in April, 2005 (NT dollar)

**Amount of previous payment (NT dollar)**

**PAY_AMT1:** Amount of previous payment in September, 2005 (NT dollar)

**PAY_AMT2:** Amount of previous payment in August, 2005 (NT dollar)

**PAY_AMT3:** Amount of previous payment in July, 2005 (NT dollar)

**PAY_AMT4:** Amount of previous payment in June, 2005 (NT dollar)

**PAY_AMT5:** Amount of previous payment in May, 2005 (NT dollar)

**PAY_AMT6:** Amount of previous payment in April, 2005 (NT dollar)

**default.payment.next.month:** Default payment (1=yes, 0=no)

## **Approach:**
To perform **Exploratory Data Analysis** on CREDIT CARD FRAUD PREDICTION , we imported Python libraries like
Numpy, **Pandas**, **Matplotlib**, **Seaborn** and Plot to display the analysis dataset and also imported from Sk learn preprocessing
data using standard scaler, and importing logistic regression,  **Random Forest Classifier**, **XG boost** classifier
for predicting Defaulter getting accuracy for finding CREDIT CARD FRAUD PREDICTION and in Graphical form
through Bar Plot, count plot, Histogram and Heatmap etc. Statistical graphics and other Data visualization methods are used
to summarize their main characteristics of “CREDIT CARD FRAUD PREDICTION”.
![image](https://user-images.githubusercontent.com/114734243/227273953-64e0eda3-15cf-48eb-9163-9c2bdfa0cf11.png)

![image](https://user-images.githubusercontent.com/114734243/227273631-55876a7f-d57e-4767-8feb-8369595ec7e2.png)

![image](https://user-images.githubusercontent.com/114734243/227274145-118d0bf7-2e81-4b1a-96e5-c5a1935b8b45.png)

![image](https://user-images.githubusercontent.com/114734243/227274200-45056430-c954-4c7f-9b31-22810d2a1a04.png)




# **Conclusion**
I have predicted the defaulters using multiple models in this project.We have used Logistical regression, Random forest, XGBoost,Decision Tree, SVM. We have also used GridSearchCV to tune hyperparameters.

### 1. **From all baseline model, Random forest classifier shows highest test accuracy, F1 score and AUC.**
### 2. **Baseline model of Random forest and decision tree shows huge difference in train and test accuracy which shows overfitting.**
### 3. **The important metric to compare all the algorithms in this case is ‘Recall’. As the company can’t afford to predict False negative i.e. predict defaulter as a non defaulter. Since, company is one, who will give to money to the customers,if, for any reason giving money to defaulter is gaining more risk to getting the investment back. Hence, here identifying false negative is important.**
### 4. **We have also seen the class imbalance so we did SMOTE to handle imbalance.**
### 5. **We did train test split and stratify the target variable**.
### 6. **After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87.10% and AUC is 0.873.**
### 7. **Cross validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.**
