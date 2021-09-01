# Aviation-Reports-Classification

Code exhibited is a part of my master's thesis: Risk prediction and aviation safety report classification using Natural Language Processing (NLP), Random Forest (RF), and Bidirectional Encoder Representations (BERT) methodology. 

The dataset was relatively small, with just about 3000 aviation safety reports. 
The data used for model development were the description of the occurrence (free-form text) and the elements of event risk level classification.

The goal was to develop and compare supervised machine-learning models for predicting occurrence safety risk classification.

The project includes report narratives pre-processing, restructuring the risk level classification (to better fits target goal but still maintaining the given relationship between occurrence risk level classification), two different text representations (Term Frequency - Inverse Document Frequency and BERT), and two classification models (Random Forest and BERT). 

Models are evaluated using standard measures (Precision, Recall, and F1-score) and presented in the Confusion Matrix.

The root causes for relative poor results are analyzed and discussed.



