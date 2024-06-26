# Machine-Learning-Model-for-Weather-Forecasting
Purpose of this project is to predict the temperature using different algorithms like linear regression, random forest regression, and Decision tree regression. The output value should be numerically based on multiple extra factors like maximum temperature, minimum temperature, cloud cover, humidity, and sun hours in a day, precipitation, pressure and wind speed.

# USE OF ALGORITHMS: 

There are different methods of foreseeing temperature utilizing Regression and a variety of Functional Regression, in which datasets are utilized to play out the counts and investigation. To Train, the calculations 80% size of information is utilized and 20% size of information is named as a Test set. For Example, if we need to anticipate the temperature of Kanpur, India utilizing these Machine Learning calculations, we will utilize 8 Years of information to prepare the calculations and 2 years of information as a Test dataset. The as opposed to Weather Forecasting utilizing Machine Learning Algorithms which depends essentially on reenactment dependent on Physics and Differential Equations, Artificial Intelligence is additionally utilized for foreseeing temperature: which incorporates models, for example, Linear regression, Decision tree regression, Random forest regression. To finish up, Machine Learning has enormously changed the worldview of Weather estimating with high precision and predictivity. What's more, in the following couple of years greater progression will be made utilizing these advances to precisely foresee the climate to avoid catastrophes like typhoons, Tornados, and Thunderstorms.

# METHODOLOGY

The dataset utilized in this arrangement has been gathered from Kaggle which is “Historical Weather Data for Indian Cities” from which we have chosen the data for “Kanpur City”. The dataset was created by keeping in mind the necessity of such historical weather data in the community. The datasets for the top 8 Indian cities as per the population. The dataset was used with the help of the worldweatheronline.com API and the wwo_hist package. The datasets contain hourly weather data from 01-01-2009 to 01-01-2020. The data of each city is for more than 10 years. This data can be used to visualize the change in data due to global warming or can be used to predict the weather for upcoming days, weeks, months, seasons, etc.
Note: The data was extracted with the help of worldweatheronline.com API and we cannot guarantee the accuracy of the data.
The main target of this dataset can be used to predict the weather for the next day or week with huge amounts of data provided in the dataset. Furthermore, this data can also be used to make visualization which would help to understand the impact of global warming over the various aspects of the weather like precipitation, humidity, temperature, etc. 

In this project, we are concentrating on the temperature prediction of Kanpur city with the help of various machine learning algorithms and various regressions. By applying various regressions on the historical weather dataset of Kanpur city we are predicting the temperature like first we are applying Multiple Linear regression, then Decision Tree regression, and after that, we are applying Random Forest Regression.

Historical Weather Dataset of Kanpur City:

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/a6d335b0-d004-486b-a4cd-6903462d1e9d)

Plot for each factor for 10 years

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/fa1e39a9-87a7-45c3-b777-0d6a95b7fa7a)


Plot for each factor for 1 year

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/24e4ce74-81cd-43fd-bec4-11159504bdb0)


![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/5ed2ae24-aeff-4383-8fcd-581262e7ff17)


# Multiple Linear Regression: 
This regression model has high mean absolute error, hence turned out to be the least accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 

 ![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/42b599e0-55df-4986-b7f1-0ed1c7746fbb)


# Decision Tree Regression: 
This regression model has medium mean absolute error, hence turned out to be the little accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/29eb7821-164c-43de-bbfd-df67011b1cae)

# Random Forest Regression: 
This regression model has low mean absolute error, hence turned out to be the more accurate model. Given below is a snapshot of the actual result from the project implementation of multiple linear regression. 

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/8f0879f2-1c1d-4a3d-8248-f6f948aa13ac)

# R2-score for Multiple Linear Regression:

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/2e48d676-9f06-49fc-a8e6-5a09b94acde0)

# R2-score for Decision Tree Regression:

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/3a5123e2-3ed7-450c-bf2e-142d273c749c)

# R2-score for Random Forest Regression:

![image](https://github.com/Rajeshd01/weather-forecasting/assets/97429910/c7078901-001b-405d-9818-b5b68c7c17e5)




