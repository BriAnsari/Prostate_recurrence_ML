
#Background:
More than half of Prostate cancer patients are at risk of developing recurrence. Current recurrence risk
tools based on clinical risk factors do not take multi-omics data into consideration. A prediction model
that integrates clinical parameters with multi-omics data can offer a more personalized recurrence risk
score. The goal of this study was twofold; first, to develop a supervised ML recurrence risk prediction
model based on transcriptomic and clinical risk factors; second, to create a user-friendly web application
that can quantify prostate cancer recurrence risk.

#Methods:
The study population comprised 393 prostate cancer patients from The Cancer Genome Atlas (TCGA)
database. Feature selection was performed on the available phenotype and transcriptomic data to create
a final dataset for model development. We developed and compared five supervised ML models. The
model with the highest AUC was selected.

#Results:
The study population comprised prostate cancer patients with recurrence (n=322) and without recurrence
(n=71). The median age for both groups was 61 years. Patients with recurrence had a significantly higher
Gleason score and more advanced disease than those without recurrence (P < .001). Logistic regression
with ridge regression (L2) was selected based on the highest predictive performance (AUC:0.75) amongst
all the models and a balanced sensitivity (0.8) to specificity (0.6) ratio. The feature importance plot
showed that Loc440173, Gleason score, and fam36a had the most influence on the predicted outcome.

#Web App:
Logistic regression(L2) tidy model workflow was built into a web application. The app reacts to user inputs
to show the probability of prostate cancer recurrence.

#Conclusion:
Our risk prediction model based on logistic regression (L2) performance was comparable to an existing
model (AUC: 0.75 vs. 0.78). The most important and biologically plausible features were Loc440173,
Gleason score and fam36a. 
