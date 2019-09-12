# *Data Science Portfolio*
#### -*Harshul Varma*
***
## About me:

Over the years I have developed a passion to solve problems using analytical techniques while using latest technologies. I believe in constant learning and applying the gained knowledge to meaningful projects.

This portfolio consists of projects I've worked on to demonstrate my skills in various aspects of Data Science (data cleaning, data visualisation, data analysis and machine learning)

Tools I use/currently learning: Python (pandas, matplotlib, seaborn, plotly, scikit-learn, tensorflow, Keras), SQL, Tableau, d3.js, R

[LinkedIn](https://www.linkedin.com/in/harshulvarma/)

***
## Projects:

### [Analysing and Predicting Customer Retention](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Customer_Churn.ipynb)
- **Exploratory Data Analysis** of customer churn behaviour based on 26 features such as demographics, services, billing and charges
- Discovered most important features that are responsible for customer churn using **Random Forest Classifier**
- Developed a **Logistic Regression** model to predict whether a customer is likely to leave or not

![customer_churn](Images/customerchurn.png)

***
### [Segmenting customers based on Credit Card usage](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Credit_Card_User_Segmentation.ipynb)
- Segmented customers based on credit card usage for banks to target clusters with appropriate marketing strategies
- Discovered highly correlated features using Pearson correlation and feature engineered the dataset
- Utilised K-Means in scikit-learn for cluster analysis and PCA (Principal Component Analysis) to visualise clusters

![credit_card](Images/CreditCard.png)

***
### [Air quality analysis and prediction - Madrid](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/air_quality_analysis_and_prediction_Madrid.ipynb)
- Analysed effect of altitude on pollution levels in Madrid air stations
- Clusterd and anlaysed similiar air stations using **K-Means**
- Visualised yearly, monthly and hourly trends of 2001-2018 major pollutant levels
- Modelled and Evaluated Long Short Term Memory-Recurrent Neural Network (**LSTM-RNN**) to predict NO2 levels

![air_quality](Images/PredictedNO2.png)

***
### [Pneumonia detection in X-Ray Images](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Pneumonia_X-Ray_Images.ipynb)
- Implemented **transfer learning** using fine-tuned **ResNet50** architecture in Keras to predict Pneumonia in X-Ray images 
- The dataset was evaluated on various machine learning algorithms and neural network architectures but yielded best results using ResNet50 with Data Augmentation
- The final model is evaluated based on Accuracy, F1 Score, Precision and Recall

![xray_1](Images/XRay.PNG)![xray_2](Images/PneumoniaConfusion.PNG)

***
### [Finding Similiar Neighborhoods -Toronto](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Finding_Similar_Neighborhoods.ipynb)
- Scraped, cleaned and analysed Toronto postal area, borough and neighbourhood data
- Used **Foursquare API** to get popular venues in each neighborhood
- Clustered neighborhoods based on common venues using **K-Means unsupervised learning**
- Found similiar neighborhoods based on euclidean distances

![toronto_clusters](Images/TorontoClusters.JPG)

***


