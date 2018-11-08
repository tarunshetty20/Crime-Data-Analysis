# Crime Data Analysis using Machine Learning Algorithms
The crime dataset that we chose has real data and is acquired from UCI Machine Learning repository where the title of the dataset is 'Crime and Communities'. The dataset has large number of numerical columns which was the main reason for choosing such a dataset rather than a categorical one because it makes is easy to apply algorithms and avoids the hassle of conversion of categorical data to numerical data. The crime attributes in the dataset that could be predicted by applying various machine learning algorithms as considered by the FBI are Rape, Murder, Larceny, Robbery, Assault, Burglaries, Autotheft and Arsons.

The other columns in the dataset include information about community names, county codes, community codes, percent of the population considered urban, age based population, gender based population, race based population and so on which are useful factors to predict crimes. We used some features as predictors from the dataset to train the different models and created a binary label to predict the Occurence of Crime based on the selected features. We also calculated various metrics like accuracy, f1 score, rms value, confusion matrix for the various clustering, regression and classification algorithms that we applied to the dataset.

The state column which was missing from the dataset was added to it based on the enrichment dataset viz cities.json available on the link below which contains mappings of latitude and longitude co-ordinates to their respective cities and states.

Base and Enrichment Dataset Location: https://www.kaggle.com/kkanda/analyzing-uci-crime-and-communities-dataset/data

To the data set the below machine learning algorithms are applied
* KMeans
* GMM
* Linear Regression
* Logistic Regression
* Decison Trees
* Naive Bayes
* Random Forests
* Support Vector Machine
* Principal Components Analysis
* KNN

Thereby all these algorithms are applied to different use cased based on the problem type whether it is a Classification, Regression ot Clusterring problem. Finally a story is formed which gives a conclusion of the crime analysis.
