# [Kaggle-Bike-Sharing-Prediction](https://www.kaggle.com/c/bike-sharing-demand/overview)

## Notebook: [kaggle-bike-sharing.ipynb](https://github.com/owenpb/Kaggle-Bike-Sharing-Prediction/blob/main/kaggle-bike-sharing.ipynb)

### Forecasting use of a city bikeshare system

The data set for this competition consists of $10900$ records of bike rentals over a two year period in Washington D.C. as part of the Capital Bikeshare program. Each record lists the total number of bikes rented within a one hour window, along with various weather and date information. There is a mixture of categorical data types (weather type, season, holiday status, and work day status) and continuous weather data (temperature, humidity, windspeed, etc.) which we will use to forecast bike rental demand on a test set prepared by Kaggle for this competition.

Since our task is to predict a numerical value (bike count) we employ a variety of regression algorithms. In particular, we explore:<br>

**1. Linear Regression**<br>
**2. Ridge Regression**<br>
**3. Lasso Regression**<br>
**4. K-Nearest Neighbors**<br>
**5. Decision Tree**<br>
**6. Random Forest**<br>
**7. AdaBoost**<br>
**8. XGBoost**<br>

After tuning hyperparameters with GridsearchCV, our best model achieves a test score within the **top 5%** of the Kaggle leaderboard. For additional details and background information related to this dataset, see the Kaggle competition page at [https://www.kaggle.com/c/bike-sharing-demand/overview](https://www.kaggle.com/c/bike-sharing-demand/overview).