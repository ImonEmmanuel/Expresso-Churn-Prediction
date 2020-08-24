## Expresso-Churn-Prediction

<a href = "https://zindi.africa/hackathons/dsn-pre-bootcamp-hackathon-expresso-churn-prediction-challenge"><b>Competition Link</b>

<b>DSN Pre-Bootcamp Hackathon: Expresso Churn Prediction Challenge by Data Science Nigeria This solution will help Expresso to better serve their customers by understanding which customers are at risk of leaving.</b>

My Solutions was doing Exploratory Data Analysis, Created New columns from the TOP_PACK columns in the dataset.

I used three diffrent approach for my solutions Model using Kmeans to create cluster, Log Transfroming the Skewed Columns and No preprocessing with each given me a higher logloss than my baseline model of (Public LB: 0.2519) 

<h3>Solution WorkThrough</h3>

1. Exploratory Data Analysis
2. Using Sklearn Label Encoder for Encoding Categorical Features
3. Kmeans Clustering
4. Ensembling


<h3> Improvement </h3>

1. Feature Engineering
2. Selecting the Besy K for the Kmeans Clustering
3. Using Pandas Get Dummy Method for Encoding the REGION Features

My Score was a blending of the 3 Model (Log Transform Model, Model, Cluster Model) 

Public LB: 0.25137 39/358

Private LB: 0.24713 27/358

If you have any questions or suggestions do not hesitate to contact me on  <a href = "https://www.linkedin.com/in/imonemmanuel"><b>linkedin<b>
