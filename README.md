# Data science portfolio by Konstantin Parfenov

This portfolio is a compilation of my data science and machine learning projects in recent years.

## Stand-alone projects.
### Energy market counterparty bankruptcy prediction analytics system 
A client for this project is Rosenergoatom JSC. The task is to predict bankruptcy for a counterparty on a Russian wholesales energy and capacity market. 

Fundamental data extracting and transformation procedures are written in SAS Base/Macro language and scheduled daily. Scripts combine raw payment data, data from corporate sources, various scrapped data from .pdf and .html files and put them in an Oracle database. The connection between Oracle database and Atomcloud ("IBM Cloudpak for data" deployed on [Data center Kalininsky](https://www.rosenergoatom.ru/stations_projects/opornyy-tsod/)) approved by the internal Information Security Department.

Python script, which executes on a dedicated runtime described in the environment management tab, performs further data transformation, data cleaning, and data quality check. 

Model compares 6 approches:

* Logistic Regression
* Knearest Neighbours
* Support Vector Classifier
* Decision Tree Classifier
* MLP Neural Network Classifier
* Gradient Boosting Classifier

Prediction results from both, Gradient Boosting Classifier and MLP Neural Network Classifier are represented in an analytical dashboard.

[RUS Rosenergoatom JSC presentation](https://github.com/Konstantin-Parfenov/Konstantin-Parfenov.github.io/files/6722061/_._.pptx)
[RUS Short video of product description for Rosatom CEO (Alexey Likhachev)](https://user-images.githubusercontent.com/6107160/123541038-e5547000-d74a-11eb-9464-9e36329f4a12.mp4)

### Sibur PET-price Prediction
[PET price price prediction dashboard for Sibur analytics.](https://siburdashboard.herokuapp.com/#)  Created in 2019 at Sibur Hackathon. 
[Github](https://github.com/Konstantin-Parfenov/Sibur_dashboard)
![Dashboard image](https://user-images.githubusercontent.com/6107160/123554092-266a7580-d787-11eb-9ede-6b09d4d6df0a.jpg)


Features:

* [Predictions based on Exponential Moving Average (EMA) and Simple Moving Average (SMA)](https://siburdashboard.herokuapp.com/forecast_chart/EMA)
* [Feature importances graph](https://siburdashboard.herokuapp.com/forecast_pie)
* Dashboard built using flask model view controller structure and javascript.
* Deploy on heroku via heroku CLI.
* Frontend theme is a modified free template from [Creative Tim](https://www.creative-tim.com/)

### Sibur Fraction Mix Prediction

### DMP-System user classifiation


## 

## Big data Spark Projects

### RecSys for videocontent Megafon

[Github](https://github.com/Konstantin-Parfenov/RMSE_rec_sys/blob/main/Rec_sys.ipynb)

Task is to create the best RecSys algorithm based on RMSE metrics.
Data on HDFS. Result RMSE<0.83

### 

## Kaggle competitions.








