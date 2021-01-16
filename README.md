## Credit Card Fraud Detection
Performed detailed analysis on the Credit Card Kaggle dataset to detect anomalies and study important features. Built an anamoly detection model to predict Frauds with 0.93 AUROC score.
Info : 
  1. Dataset: Kaggle Credit Card Dataset (https://www.kaggle.com/mlg-ulb/creditcardfraud)
  2. Credit-card-fraud notebook: 
        a. Contains EDA and data analysis. Feature exploration to understand value and role of each feature present in dataset.
        b. Synthetic Minority Oversampling Technique (SMOTE) to oversample the minority class to balance the class distribution. (https://arxiv.org/abs/1106.1813)
        c. CATBOOST: gradient boosting on decision trees (https://github.com/catboost/catboost). Used here to build the anamoly detection Model
        
  3. GAN-credit-card-fraud notebook:
        a. Contains EDA and data analysis. Feature exploration to understand value and role of each feature present in dataset.
        b. Generative Adversarial Network (GAN): Used GAN to generate fake data points. Generated 5000 rounds with 29 features in each of the 3 epoochs. 
          (http://cs230.stanford.edu/projects_winter_2020/reports/32635168.pdf) 
          (https://www.toptal.com/machine-learning/generative-adversarial-networks)   
          (https://github.com/krantirk/Credit-GANS)
        c. CATBOOST: gradient boosting on decision trees (https://github.com/catboost/catboost). Used here to build the anamoly detection Model
