# Group 52: COMP90051 Statistical Machine Learning Project: Human vs Machine text Classifier
In this project, the dataset consists of text samples labelled as either human- or machine-generated, drawn from two distinct domains. The domain and class labels of the training data is known, while both labels are unknown for the testing data. The aim is to develop a classifier that effectively distinguishes between human and machine-generated text. 

We evaluate three approaches: Naive-Bayes, Logistic Regression, and a Multitask CNN model. The multitask CNN has the main task is to classify text as human or machine-generated, while the secondary task is to predict the text's domain. By jointly learning two tasks, the Multitask CNN performs the best among the three approaches because it can incorporate domain information, which can be an important feature for classifying human or machine-generated text . 

Model developments and implementations are presented in the final_model.ipynb. The notebook uses standard libraries except 'optuna', which we have already included the code to install it in the notebook.
