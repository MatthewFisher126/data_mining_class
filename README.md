# Data mining class project
Supervised machine learning project where I wanted to see if I could detect credit card fraud using two different methods. I compared a Random Forest and an ensemble approach which combined a Random Forest + Complement Naive Bayes algorithm. To account for the imbalanced dataset I used a technique called Synthetic Minority Over-sampling TEchnique (or SMOTE) which allowed me to bring up the minority or fraud cases to the same as non-fraud cases. As for the ensemble approach, I did this using a voting classifier to choose the highest probability between the two models. The Random Forest algorithm slightly outperformed the ensemble approach in most evaluation metrics (precision, recall, specificity, accuracy, Matthews Correlation Coefficient - 0.807 vs 0.797, respectively).

[Project/Code](https://github.com/MatthewFisher126/data_mining_class/blob/main/credit-card-fraud-project.ipynb)

[Paper](https://github.com/MatthewFisher126/data_mining_class/blob/main/Credit%20Card%20Fraud%20Protection%20Paper.pdf)
