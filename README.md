# cancer_clinical_trials_prediction
Given type of study and short description of disease, I build a model to predict the eligibility or qualification of the patient for the clinical trials.<br/>


My approach to the problem:--- <br/>

tokenize the list of sentence  <br/>
convert it into sequences  <br/>
Find the coefficient of words using GLoVE that is pre-trained word embeddings  <br/>
Find embeddings for indexes <br/>
Apply Deep Learninng model for prediction <br/>
