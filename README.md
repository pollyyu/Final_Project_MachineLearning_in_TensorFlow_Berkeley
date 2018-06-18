# Final_Project_MachineLearning_in_TensorFlow_Berkeley
This is the final project of Berkeley extension's Machine Learning Course in TensorFlow.

Project Proposal: 

The dataset, obtained from Kaggle is a list of ~20,000 recipes listed by rating, nutritional information and assigned category that is already parsed. I plan to predict the public rating of recipes based on continuous and categorical features given in the dataset. 

The feature size is large (678 count) but extremely sparse. Hence, I believe that the dataset would make a great candidate to build a model combining wide linear model and a deep feed-forward neural network (using DNNLinearCombinedClassifier). The wide linear model is able to memorize interactions with data but not able to generalize learned interactions on new data. The deep model generalizes well but is unable to learn exceptions within the data. It is intended that the wide and deep model combines the two models and is able to generalize while learning exceptions (https://arxiv.org/abs/1606.07792).


