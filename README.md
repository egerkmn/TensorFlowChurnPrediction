# TensorFlowChurnPrediction

In this project, I will implement a Multilayer Perceptron on a churn classification problem via TensorFlow. The dataset contains 10000 rows and 14 columns including customer information. The binary target variable is given in Exited column. Since our dataset is imbalanced, AUC ROC will be used as a evaluation metric as well as accuracy.

We will go through 5 steps:
1) **Preparing Libraries and Data:** Obtaining and investigating the dataset 
2) **Preprocessing the Data:** Enconding categorical variables and scaling numerical variables
3) **Evaluation Metric and Base Score:** Base score assumption
4) **Building the MultiLayer Perceptron for Binary Classification:** Implementing TensorFlow MLP model
5) **Another Trial with a Sampling Method for Imbalanced Datasets:** Improving the evaluation scores with a resampling method

More details are given in the Jupyter Notebook.
