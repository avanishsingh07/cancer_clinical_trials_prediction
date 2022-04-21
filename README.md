# cancer_clinical_trials_prediction
Given type of study and short description of disease, I build a model to predict the eligibility or qualification of the patient for the clinical trials.


My approach to the problem:--- \n

tokenize the list of sentence  \n
convert it into sequences  \n
Find the coefficient of words using GLoVE that is pre-trained word embeddings  \n
Find embeddings for indexes \n
Apply Deep Learninng model for prediction \n
