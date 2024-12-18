# Bank Marketing Analysis Project

This project analyzes the likelihood of clients subscribing to a term deposit following a direct marketing campaign. Using a logistic regression model and other statistical methods, the study identifies significant factors that influence client behavior and provides actionable insights for optimizing marketing strategies.

### Overview
The objective of this project is to determine how the bank can optimize its direct marketing strategies to increase the likelihood of clients subscribing to a term deposit. We utilized demographic, financial, and campaign-related variables to identify key factors that influence client decisions.

### Data Overview
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Source: [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)

Size: 45211 observations and 17 variables

Resampling technique: Undersampling to balance y


### Business and Analytics Questions 

**Business Question:** _How can the bank optimize its direct marketing strategies to increase the likelihood of clients subscribing to a term deposit?_ 

**Analytics Question:** _What factors contribute to a client’s likelihood to subscribe to a term deposit following a direct marketing campaign?_”

### Data Description
The dataset contains client-level information collected from a marketing campaign, including demographic, financial, and campaign-related variables.

Key variables analyzed include:

**Demographic:** Age, job, marital status, education.

**Financial:** Account balance, loan status, housing loan status.

**Campaign-Related:** Call duration, number of contacts, and previous campaign outcomes.



### Methodology

**Exploratory Data Analysis (EDA):** Visualized and summarized the data to identify patterns and trends.

**Logistic Regression Model:** Applied to identify significant predictors of subscription likelihood.

**Validation:** Results were cross-validated using random forest and decision tree models.


### Key Findings
1. **Demographic Factors:**

Clients with tertiary education and students are significantly more likely to subscribe.

Age and marital status were not statistically significant predictors.


2. **Financial Factors:**

Clients without housing loans or personal loans are more inclined to subscribe.

Higher account balances are positively associated with subscription likelihood.


3. **Campaign-Related Factors:**

Longer call durations significantly increase the likelihood of subscription.

Excessive contact attempts reduce the likelihood of subscription.



### Collaborators
This project was a team effort, with contributions from the following team members:

**Shu-Wen Teng,**

**Soyoung Yoon,**

**Yen-Jo Lee,**

**Yen-Chun Lin**


### Acknowledgments
We thank our course instructor **Henry Ho** for their guidance throughout the project. Special thanks to our team members for their collaboration and dedication.


