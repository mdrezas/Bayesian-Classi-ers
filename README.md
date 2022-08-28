# Bayesian-Classifers
Naive Bayes and kNN to predict the presence of heart disease in the patient based on the Cleveland database.
train two Bayesian classifiers (Naive Bayes and k-NN) to predict the presence of heart disease in the patient based on the Cleveland database. 
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them, such as age, sex and several medical predictor variables.
You can find more details of the data on the Kaggle website.

Tasks:

Download the data. Create an account with Kaggle (if you have not previously
done so) and download the Heart Disease dataset. You should split the 303 in-
stances into training and test sets (8:2) for Naive Bayes classier. While for the
k-NN classifier, you need to split the instances into training, validation, and test
sets as (6:2:2). The validation set is used to fine-tune the hyper-parameter k. Data
can be downloaded from https://www.kaggle.com/ronitf/heart-disease-uci.

Train your Naive Bayes and k-NN Classifiers on the training set.

After training, test them on the test set, construct confusion matrices (accuracy,
precision, recall, and F-score) for the testing set results, and show these confusion
matrices.

Guidelines:
Use Euclidean distance (L2) to compute distances between instances. As the
attributes in Heart Disease dataset are either categorical or continuous. In the
case of mix of these two, the categorical variables may be mapped to numerical
values (through one-hot encoding) before applying the k-NN algorithm.

Each continuous feature should be normalized separately from all other features.
Speciacally, for both training and testing instances, each feature should be trans-
formed using function F(X) = (X 􀀀 mean)=std, using the mean and std of the
values of that feature on the training data.
