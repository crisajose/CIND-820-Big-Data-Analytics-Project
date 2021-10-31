# CIND-820-Big-Data-Analytics-Project
The objective is to build a predictive model that accurately classifies risk and also evaluate the risks presented by new business in order to determine acceptance or decline of the new business.

The dataset used is https://www.kaggle.com/c/prudential-life-insurance-assessment/overview which is a public dataset available in Kaggle. Prudential Life Insurance announced a competition in Kaggle in 2016 that invited data scientists to come up with a risk assessment model. The data set consists Train and Test data which describe the characteristics of life insurance applicants. It comprises of nominal, continuous and discrete variables, which are anonymized. It consists of Train data with 59381 clients and test data with 19765 clients and 127 features each. We have to predict the Response variable which ranges from 1 to 8. 8 indicates the highest risk level.

# The data
This repository contains a train and test dataset. train.csv - the training set, contains the Response values test.csv - the test set, you must predict the Response variable for all rows in this file

![image](https://user-images.githubusercontent.com/91291523/139596895-d6229796-120e-42c9-abec-82cf1e09639e.png)



The following variables are all categorical (nominal):

Product_Info_1, Product_Info_2, Product_Info_3, Product_Info_5, Product_Info_6, Product_Info_7, Employment_Info_2, Employment_Info_3, Employment_Info_5, InsuredInfo_1, InsuredInfo_2, InsuredInfo_3, InsuredInfo_4, InsuredInfo_5, InsuredInfo_6, InsuredInfo_7, Insurance_History_1, Insurance_History_2, Insurance_History_3, Insurance_History_4, Insurance_History_7, Insurance_History_8, Insurance_History_9, Family_Hist_1, Medical_History_2, Medical_History_3, Medical_History_4, Medical_History_5, Medical_History_6, Medical_History_7, Medical_History_8, Medical_History_9, Medical_History_11, Medical_History_12, Medical_History_13, Medical_History_14, Medical_History_16, Medical_History_17, Medical_History_18, Medical_History_19, Medical_History_20, Medical_History_21, Medical_History_22, Medical_History_23, Medical_History_25, Medical_History_26, Medical_History_27, Medical_History_28, Medical_History_29, Medical_History_30, Medical_History_31, Medical_History_33, Medical_History_34, Medical_History_35, Medical_History_36, Medical_History_37, Medical_History_38, Medical_History_39, Medical_History_40, Medical_History_41

The following variables are continuous:

Product_Info_4, Ins_Age, Ht, Wt, BMI, Employment_Info_1, Employment_Info_4, Employment_Info_6, Insurance_History_5, Family_Hist_2, Family_Hist_3, Family_Hist_4, Family_Hist_5

The following variables are discrete:

Medical_History_1, Medical_History_10, Medical_History_15, Medical_History_24, Medical_History_32

Medical_Keyword_1-48 are dummy variables.

# Overall methodology and Process flow

![image](https://user-images.githubusercontent.com/91291523/139596968-e30525f9-db7b-45f0-821b-33ecb30f6d31.png)
