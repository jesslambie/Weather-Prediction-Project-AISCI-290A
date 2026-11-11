# Weather-Prediction-Project-AISCI-290A
This is the first project for AISCI 290A. It investigates whether historical weather data can be used to make weather predictions in Seattle, Washington. The research question is: Can historical temperature and precipitation data accurately predict daily temperature and precipitation?

The project uses data from the ERA5 database containing daily means of temperature, pressure, precipitation, and wind speed for 2009 and 2010 in the continental U.S. The testing parameters for this project are temperature and precipitation. 

After cleaning the data, I tested three different models. The linear regression model serves as the baseline model. The second model builds on the baseline model by adding 3-day and 7-day rolling averages to see if adding new features will improve weather predictions. The final model utilizes a neural network (MLPRegressor) to test whether more complex relationships can improve predictions. 

All three models are analyzed through prediction errors, specifically the mean absolute error to compare their prediction performance. 

This project was developed and run in Jupyter notebook using the conda 290A environment, and imported into the github repository.