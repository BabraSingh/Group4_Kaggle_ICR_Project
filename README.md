# Group4_Kaggle_ICR_Project
https://www.kaggle.com/competitions/icr-identify-age-related-conditions/data - the link to access the competition.  Following were the team members: 
SUBMITTED BY – GROUP 4 VANSHIKA (SID: 041044413) SARTAJ SINGH BABRA (SID: 041094831) NAITIK TALATI (SID: 041084256) SAIYAM SHAH: (SID: 041080364) JAY PATEL (SID: 041085500)

ABSTRACT:
The purpose of this report is to describe the creation and testing of a predictive model for age-related illness disorders. The Invitro Cell Research, LLC (ICR) competition aims to predict whether a person has one of three age-related medical disorders (Class 1) or none of these conditions (Class 0). The model is based on anonymized measures of health parameters to protect patient privacy.
The goal of this competition is to simplify the process of determining whether someone has these medical disorders, which now includes a time-consuming and intrusive data collection process from patients. By utilizing crucial health variables while keeping patient details confidential, predictive models can assist shorten this procedure.
This competition is significant because it has the potential to help researchers find the association between health characteristic assessments and age-related medical disorders. Furthermore, it promotes developments in the fields of bioinformatics and data science by investigating novel approaches for solving essential problems using different data.

INTRODUCTION:
Age is simply a number, but aging is accompanied by a multitude of health problems. Aging is a risk factor for a wide range of illnesses and consequences, including heart disease, dementia, hearing loss, and arthritis. Research exploring therapies that can help delay and reverse biological aging and prevent serious age-related illnesses is part of the expanding discipline of bioinformatics. Even if the number of samples is modest, data science may be able to contribute to the creation of novel approaches to challenges using diverse data.
This project aims to predict if a person has any of three medical conditions. We will be predicting if the person has one or more of any of the three medical conditions (Class 1) or none of the three medical conditions (Class 0). In this report, we will create a model trained on measurements of health characteristics.
Information gathering from patients is a time-consuming and intrusive process needed to evaluate whether someone has various medical disorders. By gathering crucial variables relevant to the conditions, then encoding these features, predictive models enable us to speed up this procedure while maintaining patient confidentiality.

DATASET DESCRIPTION:
The dataset consists of three age-related diseases and more than fifty anonymized health characteristics. The variable "Class" has two potential values, with the data being a binary classification problem: 1 denotes the presence of one or more age-related conditions, while 0 denotes the absence of any of the three conditions in the subject's medical history.
The following files and fields are included in the dataset:
train.csv: The training set, includes fifty-six anonymized health characteristics and unique identifiers for each observation. The target variable is indicated by the 'Class' field.
test.csv: The test set for which the likelihood of participants belonging to each class must be predicted.
greeks.csv: Supplemental metadata accessible solely for the training set, including the type of age-related condition, three experimental characteristics, and the data collection date.

PROBLEM STATEMENT:
The competition requires competitors to create a prediction model based on training data to assess whether a subject in the test set belongs to Class 1 or Class 0. Participants are required to employ data science techniques to develop an accurate and reliable model for predicting age-related medical problems. Current models, such as XGBoost and random forest, have not performed well in predicting medical disorders. As a result, the primary goal of this challenge is to improve on existing methods and construct models that can consistently make the right predictions between diverse scenarios, especially when dealing with significant problems that affect people's lives.

Key Points:

1.The modeling was completed on the test data set whch had 617 records and 58 features
2.Out of 58 - 56 are health conditions,1 is class (Target Variable) and ID.
3. Values are missing in multiple features columns like BQ, CB, CC etc.
4. EJ one of the health condition - the data was categorical for others it was numerical
5. Histrogram was plotted to understing the distribution of the values.
6. Disribution plot was plotted to understand the distribution of target varaible in each health condition.
7. Correlation was checked amongest the health condtion and target variable.
8. Correlation was plotted to check the realtion b/w each health condtion
9. Scttarplot helped to understand the distributiion of the healthcondition
10. Box plot plotted to check the outlier and removed using IQR range.
11. Remaing missing values were replaced by mean.
12. The data normalized and standardized beforer modelling
13. 9 diffrent models with and with hyper parameter tuning were applied to check the accuracy.
14. 1 model was selected basis the score and the simplicity.
15. In our case: Logistic regression with HPT is recommended. 


