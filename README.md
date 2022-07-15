# Phishing Website Detection by Machine Learning Techniques

## Objective
The objective of this project is to train machine learning models and deep neural nets on the dataset created to predict phishing websites.

## Data Collection
The set of phishing URLs are collected from opensource service called **PhishTank**. This service provide a set of phishing URLs in multiple formats like csv, json etc. that gets updated hourly. To download the data: https://www.phishtank.com/developer_info.php. From this dataset, 5000 random phishing URLs are collected to train the ML models.

The legitimate URLs are obatined from the open datasets of the University of New Brunswick, https://www.unb.ca/cic/datasets/url-2016.html. This dataset has a collection of benign, spam, phishing, malware & defacement URLs. Out of all these types, the benign url dataset is considered for this project. From this dataset, 5000 random legitimate URLs are collected to train the ML models.

The above mentioned datasets are uploaded to the '[DataFiles](https://github.com/shreyagopal/Phishing-Website-Detection-by-Machine-Learning-Techniques/tree/master/DataFiles)' folder of this repository.



These are the algorithms used in this project to measure and comparing the model

* Decision Tree
* Random Forest
* Multilayer Perceptrons
* XGBoost
* Autoencoder Neural Network
* Support Vector Machines


