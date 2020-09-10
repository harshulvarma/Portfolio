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

### [IBM Customer Churn Prediction](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/CustomerChurn.ipynb)
- Conducted Exploratory Data Analysis to understand which features contribute most to customer churn by visualizing data using seaborn
-	Predicted if a customer is likely to leave by building a XGBoost classifier to develop focused retention programs
-	Implemented feature engineering to increase model performance and interpretability


![customer_churn](Images/customerchurn.png)

***
### [Finding Similiar Neighborhoods -Toronto](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Finding_Similar_Neighborhoods.ipynb)
- Scraped, cleaned and analysed Toronto postal area, borough and neighbourhood data
- Used Foursquare API to get popular venues in each neighborhood
- Clustered neighborhoods based on common venues using K-Means unsupervised learning
- Found similiar neighborhoods based on euclidean distances

![toronto_clusters](Images/TorontoClusters.JPG)

***

### [Air quality analysis and prediction - Madrid](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/air_quality_analysis_and_prediction_Madrid.ipynb)
-	Visualised 18 years of time series data of Madrid’s air pollution to discover trends and seasonality
-	Clustered air stations in Madrid based on pollutant levels using K-means to find key areas in Madrid with highest pollution
-	Forecasted pollution level for next 2 years by modelling and evaluating a Long Short-Term Memory-Recurrent Neural Network (LSTM-RNN) using Keras and Tensorflow


![air_quality](Images/PredictedNO2.png)

***
### [Pneumonia detection in X-Ray Images](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Pneumonia_X-Ray_Images.ipynb)
- Implemented transfer learning using fine-tuned ResNet50 architecture in Keras to predict Pneumonia in X-Ray images 
- The dataset was evaluated on various machine learning algorithms and neural network architectures but yielded best results using ResNet50 with Data Augmentation
- The final model is evaluated based on Accuracy, F1 Score, Precision and Recall

![xray_1](Images/XRay.PNG)![xray_2](Images/PneumoniaConfusion.PNG)

***

### [Segmenting customers based on Credit Card usage](https://nbviewer.jupyter.org/github/harshulvarma/Portfolio/blob/master/Credit_Card_User_Segmentation.ipynb)
- Segmented customers based on credit card usage behaviour for banks to target clusters with appropriate marketing strategies:
-	Discovered highly correlated features using Pearson correlation to feature engineer the dataset
-	Utilised K-Means in scikit-learn for cluster analysis and PCA (Principal Component Analysis) to visualise clusters


![credit_card](Images/CreditCard.png)

***

