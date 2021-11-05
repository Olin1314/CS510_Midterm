# CS510 Midterm Project
Github Repository for CS 510 Project: Prediction of Aromatic Rings for Cancer Kinase Inhibitors Using Random Forest Model

Premise: SRC Kinase Inhibitors are important inhibitors for cancer proteins. A distincting factor of SRC Kinase Inhibitors and their existence is their ring count
and it acts as a very important feature for these molecules. In this project, I plan on predicting aromatic ring count given a list of 20 aggregate chemical features 
and using different machine learning models for comparison analysis. I start off by developing a basic Random Forest model and in the future, I will do a comparative 
analysis of this Random Forest model and another model to see prediction accuracy and variance levels. 

Data: SRC Kinase inhibitor Dataset(xlsx file)

Output: Summary statistics of RF model on training and testing(variance level covered, rmse, etc)

Details: Data contains ~3000 molecules with smile strings and ~20 aggregate chemical features

All code is contained in the R notebook and if run, should contain comments and information on how to load dataset and what each step is doing and functioning. Make sure the dataset is in the same directory as the R notebook for the code to load dataset properly. 
