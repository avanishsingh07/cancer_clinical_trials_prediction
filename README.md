# cancer_clinical_trials_prediction
Given type of study and short description of disease, I build a model to predict the eligibility or qualification of the patient for the clinical trials.


My approach to the problem:---

tokenize the list of sentence
convert it into sequences
Find the coefficient of words using GLoVE that is pre-trained word embeddings
Find embeddings for indexes
Apply Deep Learninng model for prediction
