# Fraudent-Transaction-Detection-Project

Motivation - It is important that financial companies are able to recognize fraudulent transactions so that customers are not charged for items that they did not purchase. In this project i have implemented an anamoly detection to detect whether there is any fraudulent transaction.

Libraries used -
- Pandas
- Numpy
- Matplotlib
- Scikit Learn
- Scipy

Process -
- Imported data and checked missing values, outliers
- Did Exploratory Data analysis, identified which types of transactions where fraudent, identified trends and patterns by interogating data.
- Finding out the distribution of data, visualization of data and correlation heat map.
- Feature engineering
- Preparing data for model fitting
- Model fitting and making predictions, checking accuracy scores, confusion matrix, classification report and errors.

Machine Learning Algorithm used - Isolation Forest
- One of the newest techniques to detect anomalies is called Isolation Forest. The algorithm is based on the fact that anomalies that are few and different. As a result of these properties, anomalies are susceptible to a mechanism called isolation.

How Isolation Forests Work - the Isolation Forest algorithm observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. The logic argument goes isolating anomaly observations is easier because only a few conditons are needed to separate those cases from the normal observations. On the other hand, isolating normal observations require more conditions. Therefore, an anomaly score can be calculated as the number of conditions required to separate a given observation.

Conclusion - Accuracy score of my model was 99.31% with identified 13019 errors out of approx. 2 millions cases. The model performed very well in identifying fraudulent transactions.
