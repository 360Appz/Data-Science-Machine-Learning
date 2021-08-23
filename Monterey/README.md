
# Summary/Business Problem
Weather forecast is an important aspect of everyday life. At a macro/institutional level, forecasting helps to predict future climate expectations that may affect the area or country. At a micro level, weather affects the everyday person, forecasting helps people to plan their activities which may be affected by weather conditions. In this project, the dataset consisting of Australian cities is used, specifically, Melbourne is chosen as the main city for weather forecast.

# Method
1. Install and import packages (Prophet, Pandas, Matplotlib, os)
2. Import and read dataset
3. Data Pre-processing/Preparation ( Identify locations & data tyoes, conversion of data types, drop irrelevant columns, remove missing data)
4. Training of machine learning model (Prophet)
5. Data visualization and results

# Analysis
This dataset contains data types from text to numbers, therefore care has to be taken when using the dataset. It is important to know which fields to use for the machine learning model to get the expected forecast. Some conversion had to be done, especially the date, initially it was a text and it had to be converted to a proper date-time format.

There were also missing data approximately from 2015 to late 2016. It was removed as missing data might affect the forecasting.

The type of machine learning model used was a **neural network (AR-Net)**

**Statistics**
* Accuracy: 99%
* Mean average error (MAE): 3.02 degrees from actual value
* Data used: Daily Frequency


# Result
![](https://github.com/360Appz/Data-Science-Machine-Learning/blob/main/Monterey/Images/1%20resize.png) <br> Temperature increases towards the year end while temperatures progress lower towards the mid of the year { padding-top:5px }

![](https://github.com/360Appz/Data-Science-Machine-Learning/blob/main/Monterey/Images/2%20resize.png) <br> Temperature increases year by year { padding-top:5px }

![](https://github.com/360Appz/Data-Science-Machine-Learning/blob/main/Monterey/Images/3%20resuze.png) <br> On a nonthly basis, temperatures are higher in January, lowest in July, and increases progressively as the year ends { padding-top:5px }

# Conclusion
From the results, activities requiring moderate temperatures should be planned towards the year end. The moderate temperatures increases could also signify the coming of summer. The temperatures could be more suited to humans rather than colder weather.

It is important to note that year on year, temperatures are rising. From an institutional/ government perspective, these are problems arising from global warming. Higher temperatures cause sea level rises which affects coastal areas more significantly. Hence, action should be taken to combat rising temperatures

# References
* https://www.youtube.com/watch?v=mgX0Iz4q0bE&list=PLhusV3ueKvurI9PujkrQxMEahYTqDaAFQ&index=4
* https://github.com/nicknochnack/Forecasting-Weather-with-Neural-Prophet
* https://www.kaggle.com/trisha2094/weatheraus (Dataset)

* ### Technologies
  * Python
  * Anaconda, Jupyter Notebook
  * Prophet (Developed by Facebook, Machine Learning model)
