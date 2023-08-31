# Life_Expectancy_Prediction
Use WHO data to predict Life expectancy using Artificial neural networks  

The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The data-sets are made available to public for the purpose of health data analysis. The data-set related to life expectancy, health factors for 193 countries was collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. Among all categories of health-related factors only those critical factors  chosen which are more representative. In this project I have considered data from year 2000-2015 for 193 countries for Life expectancy prediction.  

This dataset was downloaded from https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who?select=Life+Expectancy+Data.csv

I used artifical neural networks to predict Life expectancy.  
The dataset had 22 columns. To reduce the number of features I used the K-nearest neighbors for feature selection to reduce the number of features. Finally, I used 5 most relevant features for the most accurate prediction.

