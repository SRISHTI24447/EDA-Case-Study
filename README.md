Identify patterns that help assess the risk of loan defaults.
Aid the company in decision-making regarding loan approval.
Denying loans to customers who can repay.
Approving loans to customers likely to default

(df)application_data.csv: Client information at the time of application.
(df1)previous_application.csv: Previous loan data (e.g., loan status: approved, cancelled).
(df2)columns_description.csv: Data dictionary for understanding variable meanings.


import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns 
%matplotlib inline
import warnings
warnings.filterwarnings("ignore")

 application_data.csv-
Client demographics: age, income, education
Loan details: amount, type.
Financial status: credit score, payment history.
previous_application.csv-
previous loan outcomes: approved, cancelled, refused, unused offers.


Load, clean, and merge data.
Handle missing values, duplicates, and inconsistencies.
DAYS_BIRTH column
AMT_INCOME column
AMT_GOODS_PRICE
AMT_CREDIT
OCCUPATION_TYPE
NAME_EDUCATION_TYPE
AMT_ANNUITY column
CODE_REJECT_REASON
NAME_CONTRACT_TYPE

checking is done on following columns from Application and
Pre. Application

Analysis of Application data (univariate, bivariate and multivariate), this data set 
is further divided into two data frame df_0 and df_1
Application data (univariate, bivariate and multivariate)
