Some of the projects I have completed on my data journey

## [Project 1: South Africa Rainfall Prediction - Time Series Forecasting](https://github.com/snicole2701/Time-Series-Forecasting-Rainfall-Prediction)

### Brief Description: 
This project leverages historical rainfall data from 1981 to 2025 to predict rainfall patterns for the remainder of 2025 in South Africa. The prediction model was built using time series forecasting techniques, including ARIMA, to provide valuable insights for planning and decision-making.

### Why I Took on the Project: 
My husband and I wanted to start a small vegetable garden and needed to know the best time to sprout seeds to ensure they would be ready for planting when the rains come. This helps reduce water expenses and the time spent manually watering the plants. Additionally, my family, who are farmers, also struggled with the unpredictability of rainfall in recent years. This inspired me to develop a forecasting model to assist with better planning.

### Key Features:

Data Preprocessing: Handling missing values and transforming the dataset for analysis.

Exploratory Data Analysis: Visualizing data trends and identifying outliers.

Stationarity Check: Performing the Augmented Dickey-Fuller (ADF) test.

Model Selection: Using grid search to find the best ARIMA parameters.

Model Evaluation: Evaluating the model's performance using Mean Squared Error (MSE).

Forecasting: Predicting rainfall for the next 30 days and visualizing the results.

Model Deployment: Saving the trained model and forecasted data for future use.

## Outcome Notes:
Based on the information gained from the prediction model we proceeded to plant our seeds for our summer vegetables during late August to allow enough time for our seedlings to get strong enough to be transplanted in the garden prior to the rain season. Our seedlings were ready to be planted in the garden by end September at which point we expected the rainfall to increase so we would not have to water them manually from municipal water. The first week after we transplanted them we needed to water as the rainfall was not enought to keep the vegetables happy and healthy in the summer heat. By week two the rainfall was far more regular and we only needed to water the vegetables under extreme circumstances.

The prediction was very close to accurate and allowed us to plan so we could get the most out of our vegetable garden with as little effort and cost spent on watering manually.

## Actual Rainfall since 2020

![Actual Rainfall from 2020](https://raw.githubusercontent.com/snicole2701/Time-Series-Forecasting-Rainfall-Prediction/refs/heads/main/Plot%20from%202020%20no%20forecast.png)

## Forecasted Rainfall for 2025

![Forecasted Rainfall for 2025](https://raw.githubusercontent.com/snicole2701/Time-Series-Forecasting-Rainfall-Prediction/refs/heads/main/Forecasted%20Rainfall.png)



## [Project 2: House Price Prediction Model](https://github.com/snicole2701/House-Price-Prediction-Model)

For this project, I developed a linear regression model to predict housing prices using a dataset with features like the number of rooms, population, households, and proximity to the ocean. I utilized Python in Visual Studio Code for the analysis.

### Key Features:

Data Cleaning: Handled null values and transformed skewed data.

EDA: Generated heatmaps to visualize correlations between features.

Feature Engineering: Created dummy variables for categorical data.

Visualization: Produced scatter plots to show price variations based on ocean proximity.

Model Building: Trained a linear regression model to predict house prices.

The model achieved an R-squared score of 0.669, explaining approximately 66.9% of the variability in house prices.

### Future Work:

Explore additional features and more advanced machine learning models to improve prediction accuracy.

Implement feature engineering techniques to better capture the relationships within the data.

## Outcome:
Despite the predictive model only being accurate 67% of the time, some insight was gained during the data analysis phase of the process. The scatter plot clearly shows that property prices where directly influenced based on their proximity to the coast. The Heatmap shows how certain features of the properties have a large influence on the property prices where others have little to no influence.

I will explore a different model to increase the accuracy of the model when predicting the potential price of a property for sale in the area.

In the meantime, I believe the insights gained from which features highly influence property prices we can get some value. When we know which factors have a large influence on property prices we can use this when advertising a property. Great benefit will come from emphasising feaures on a property  that have a positive impact on the potential selling price and advising selling owners on features that negatively influence the potential value of the property.

## Heatmap Of Correlation Between Features and the Median House Value

![Heatmap Of Correlation of Feature](https://raw.githubusercontent.com/snicole2701/House-Price-Prediction-Model/refs/heads/main/Heatmap%20of%20Feature%20Correlation%20after%20Ocean%20Proximity%20Inclusion.png)

## Scatter Plot of House Values Based on Proximity to the Ocean

![Scatterplot of House Values Based on Ocean Proximity](https://raw.githubusercontent.com/snicole2701/House-Price-Prediction-Model/refs/heads/main/Scatterplot%20Changes%20of%20Property%20Values%20based%20on%20Proximity%20to%20the%20Ocean.png)

