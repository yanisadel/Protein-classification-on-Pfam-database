# Project description
Kaggle link of the project : https://www.kaggle.com/datasets/googleai/pfam-seed-random-split

This project focuses on using deep learning approaches to predict the functions of protein domains, utilizing the Pfam dataset.  

The challenge involves predicting the class to which a protein domain belongs based on its amino acid sequence. The dataset comprises approximately 1 million training examples and 18,000 distinct output classes.

# Results
I achieved a **97.22% accuracy** on the test data using an ensemble method consisting of 5 CNNs (with fine-tuning of the hyperparameters).  
While I also trained other models, such as Transformers and Residual Networks, the highest performance was attained through this CNNs ensemble method.

# To run the code  
- Download the data from https://www.kaggle.com/datasets/googleai/pfam-seed-random-split  
- Put the data in the same folder than the Jupyter notebook main.ipynb.  
  The default folder name is 'random_split', but if you change it, you will need to change the DATASET_PATH in the notebook.
- Install the requirements : pip install -r requirements.txt
- You can now run the notebook
