# Cyber-Threat-Detection
Machine Learning predictive model to detect impersonation attacks

A predictive model (i.e., a machine learning classifier) capable of distinguishing between “intrusive” traffic, called threats or attacks, and “good” normal traffic (i.e., binary classification). 

Uses the impersonation attacks part of the  Aegean WiFi Intrusion/threat Dataset (AWID2),  https://icsdweb.aegean.gr/awid/awid2

## The work includes:

### Feature Generation
A Variational Autoencoder is used to generate 20 additional features to add to the data set.
 
### Feature Selection 
Filter methods are used to select the best features, generated features are included. 

### Building ML algorithms
A selection of algorithms are spot checked using K fold cross validation to find the most suitable for the data

### Tuning the models
Hyperparameter tuning is performed to tune the selected models. 

### Evaluation of models and analysis of results. 
A variety of evaluation metrics are used to assess model performance for comparison to other benchmark studies. A Naive Bayes model is selected as the best performing model for the task. 

## Final Model Diagram:

![image](https://user-images.githubusercontent.com/74421484/206158687-f483c763-1104-4c9b-98f1-22e4316135b4.png)
