# Project description
Kaggle link of the project : https://www.kaggle.com/datasets/googleai/pfam-seed-random-split

This project focuses on using deep learning to predict the functions of protein domains, utilizing the PFam dataset.

The primary goal of this dataset is to reconceptualize the PFam seed dataset as a multiclass classification task in machine learning. The challenge involves predicting the class to which a protein domain belongs based on its amino acid sequence. The dataset comprises approximately 1 million training examples and 18,000 distinct output classes.

# Results
I achieved a **99.91% accuracy** on the test data using an ensemble method consisting of 21 CNNs (with fine-tuning of the hyperparameters).  
While I also trained other models, such as Transformers and Residual Networks, the highest performance was attained through this ensemble method.
