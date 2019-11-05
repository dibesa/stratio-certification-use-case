# Model Development and Deployment
Machine Learning algorithm used to predict risk probability using German credit Dataset. Two Jupyter notebooks have been used: one of them for the model selection and the other one in order to deploy the model as microservice in DataCentric.

## Model.ipynb
Notebook where the model is developed using Python and Scikit-Learn. Before applying the model, data analysis and feature preprocessing steps has been carried out. The final selected model is a Multinomial Naive Bayes evaluated with k-fold cross validation obtaining a 74% in terms of accuracy and 72% of F-score.

## Deployment.ipynb
Notebook where the model from the previous notebook is replicated using PySpark with serialization and deployment purposes.