# Lokaesshwar-S_DataHack

I am submitting my entry for the data hack organized by GeeksForGeeks and IIT Guwahati. 

📟Objective: The aim of this project is to predict the likelihood of individuals receiving two types of vaccines: the xyz flu vaccine and the seasonal flu vaccine. This involves a multilabel classification task where we predict two probabilities for each individual.

📟Overview: The project utilizes three datasets: 
📌Training Set Features: This dataset comprises 35 features describing survey respondents. 
📌Training Set Labels: It contains target labels indicating whether each respondent received the xyz and seasonal vaccines. 
📌Test Set Features: This set includes the same 35 features for a different group of respondents, without the target labels.

📟Steps : 
1.)Loading the Test Set Features: Ensuring the test set features are correctly imported into a DataFrame. 
2.) Preprocessing the Test Set: Applying consistent preprocessing steps used for the training set to ensure uniformity and reliability. 
3.)Predicting Probabilities: Utilizing trained models to predict probabilities for both xyz_vaccine and seasonal_vaccine, and assessing model performance using ROC AUC scores on the validation set. 
4.)Generating the Submission DataFrame: Merging respondent_id from the test set with predicted probabilities to form a new DataFrame. 
5.)Saving to CSV: Exporting this DataFrame as a CSV file for submission.

📌This comprehensive approach covers all stages from initial data loading to the final submission, ensuring the development of a robust predictive model for vaccine acceptance.
