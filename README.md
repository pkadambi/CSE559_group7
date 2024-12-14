# CSE559_group7
TCR-Epitope Binding Prediction project using SETE, TCR-BERT, and TCR-T5
# Contents:
Please find the following content
- feature_extractor.ipynb, contains embedding extraction for TCR-T5, and TCR-BERT 
- pca_svr_clf_results.ipynb, contains the hyperparameter sweep, training, embedding aggregation, prompting accuracy analyses described in the results
- t5classification.ipynb, contains code to do classificaiton on TCR-T5
- SETE.ipynb, contains the code for our final submssion method SETE. This method used XGBoost with n-gram esque features, but other classifiers such as a RNN/LSTM/DNN architecture and a gradient boosting classifier were tried.

# Final Model
The final model used SETE+XGBoost
