# breast-cancer-classification-wisconsin-breast-cancer-dataset-
Detection Of Breast Cancer Using Ensemble Machine Learning Algorithm

I have used Wisconsin Breast Cancer (WBC) dataset which is taken from the UCI repository.This data set consists of 569 Cases out of which 212 are malignant and 375 are benign and it has 32 attributes.  

In the first step of the process i have gathered the Wisconsin breast cancer dataset from UCI repository the collected data is explored using exploratory data analysis by plotting various types of graphs. The data collected is the pre-processed using standardization methods. Features are selected using Univariate feature selection technique which uses ANOVA test then several classification algorithms are applied separately to register the accuracy. At the last,i have used ensemble techniques to get better accuracy.

# Exploratory data analysis (EDA)
In EDA we will look into duplicates, count of rows and columns, mean, median, missing values, quantiles, correlation between variables, data types and distribution of data. For exploratory data analysis several graphs were plotted using Matplot and Pandas profiling .Matplot is a visualization library in python which used to plot graphs for the better understanding of the data.Pandas profiling is an open source Python module with which we can quickly do an exploratory data analysis with just a few lines of code

# FEATURES SELECTION
Feature selection is a method which is used to identify the related features from the dataset and remove irrelevant and less important features. Feature selection will have huge impact on the whole performance of the model. Feature selection will reduce over-fitting, reduce training time and improves accuracy. Univariate selection, feature importance, correlation matrix with heat map are some of the feature selection techniques that are easy to use and also provide good results.Here we have utilized univariate selection  Here using univariate selection technique we selected top 20 attributes for the determination of breast cancer. univariate feature selection calculation utilized ANOVA(Analysis of Variance) test for finding detail relation between input variables and the output variable.

# Ensemble learning
An ensemble is the art of combining the decisions from multiple models to improve the overall performance.Ensemble learning which is a potent technique to improve the performance of your machine learning model.
The three most popular methods for combining the predictions from different models are bagging, boosting and voting.

# Voting
Voting is one of the easiest ways of combining the predictions from several machine learning algorithms.In this method multiple models are used to make predictions then the voting classifier is used to wrap the models by considering each models prediction as a vote.  

# XGBoost
XGBoost is an ensemble machine learning algorithm.XGBoost means extreme Gradient Boosting . XGBoost is used for both regression and classification problems. XGBoost uses the boosting technique, it builds a strong classifier by combining number of weak classifiers. XGBoost is a regularized boosting technique thus it reduces over-fitting.

# RESULTS AND DISCUSSION
we have utilized Wisconsin breast cancer (WBC) dataset. This WBC dataset is taken from the UCI repository. This data set consists of 569 Cases out of which 212 are malignant and 375 are benign and it has 32 attributes. The data collected is further pre-processed using standardization method. Since large features will impact on the model implementation we used limited input variables that are more related. Features are selected using Univariate feature selection technique. Here we have selected 20 features Since large features will impact on the model implementation. Then several classification algorithms are applied separately to register the exactness. At the last, we have utilized ensemble methods to increase the performance of the model. The accuracy achieved using ensemble learning is better than the individually achieved accuracy. The accuracy achieved using various classification algorithms and ensemble algorithms are shown below.
Logistic Regression
95.0%
KNN Classifier  
96.0%
Linear SVC
94.0%
Gaussian Kernel SVC
59.0%
Decision Trees Classifier
95.0%
BernoulliNB Classifier 
59.0%
MultinomialNB Classifier
90.0%
Artificial Neural Network 
96.0%
Voting Ensemble
97.0%
Random Forest
97.0%
XGBoost
98.0%






