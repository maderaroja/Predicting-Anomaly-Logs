# Predicting-Anomoloy-Logs

Machine Learning is helpful in many scenarios. In the current case, which pertains to predicting anomalous log files, I use techniques from Machine Learning to compute the prognostication in question. The log files are from Hadoop Distributed File System (HDFS) and are representative of Big Data as their count goes over 11 million rows of data.  
  
With the increasing prevalence of Big Data comes the increasing need to mine it efficiently for critical pieces of information that can prove beneficial to institutions, companies, and organizations as well as to the public, as witnessed with COVID19.  

The forecasting process commenced with the creation of a parser code to re-structure raw log files (HDFS). Throughout, I performed Exploratory Data Analysis to garner insights. In the end, I employed Scikit Learn Dummy and Random Forest Classification functions to perform Supervised Machine Learning on the HDFS log files. The results illustrate the successful training of the computer to correctly label log files as anomalous or as normal. The precision scores are 0.95 and 0.99 with recall at 0.60 and 1, and F1-scores at 0.74, and 0.99 respectfully.  

This repository consists of the code and results of the final stage of the process. 


# Results - Confusion Matrix

Below is a summary of the results in a Confusion Matrix


Predicting Log Anomaly
<img width="359" alt="image" src="https://user-images.githubusercontent.com/83246246/166605775-e7bed218-64a4-4a40-8af9-3e9b92cedf5b.png">

