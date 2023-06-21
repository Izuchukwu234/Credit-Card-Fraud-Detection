# Credit-Card-Fraud-Detection
Here, I will be using two popular classification models to recognize fraudulent credit card transactions. These models are: Decision Tree and Support Vector Machine. I will use a real dataset to train each of these models. The public dataset includes information about transactions made by credit cards in September 2013 by European cardholders. I will use the trained model to assess if a credit card transaction is legitimate or not.

In the current session, I will be utilizing not only the Scikit-Learn Python interface, but also the Python API offered by the Snap Machine Learning (Snap ML) library. Snap ML is a high-performance IBM library for ML modeling. It provides highly-efficient CPU/GPU implementations of linear models and tree-based models. Snap ML not only accelerates ML algorithms through system awareness, but it also offers novel ML algorithms with best-in-class accuracy. For more information, please visit [snapml](https://ibm.biz/BdPfxy?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkML0101ENSkillsNetwork1047-2022-01-01) information page.
### Introduction
Imagine that I work for a financial institution and part of my job is to build a model that predicts if a credit card transaction is fraudulent or not. I can model the problem as a binary classification problem. A transaction belongs to the positive class (1) if it is a fraud, otherwise it belongs to the negative class (0).

I have access to transactions that occured over a certain period of time. The majority of the transactions are normally legitimate and only a small fraction are non-legitimate. Thus, typically I have access to a dataset that is highly unbalanced. This is also the case of the current dataset: only 492 transactions out of 284,807 are fraudulent (the positive class - the frauds - accounts for 0.172% of all transactions).

To train the model I can use part of the input dataset and the remaining data can be used to assess the quality of the trained model. First, let's download the dataset.
