
# Close Price Prediction Model

## Overview
For this project, using python and tensorflow. I developed a model that predicts the following days closing price for a certain stock. Utilizing recurrent neural networks, specifically LSTMS, the model was able to use years worth of data to train itself and understand the patterns of the stock price given, resulting in a predicted price for the following day.
## Features
- **TensorFlow 2.0**: Utilizes tensorflow to build and train the model on the data it was given. 
- **CNNs**: Incorporates Recurrent Neural Networks, specifically LSTMS, in order to memorize trends and patterns that occur over time, and use them to predict the close price of the stock. LSTMS are very beneficial for time series data as they are able to retain memory about the information it has already been fed and decide whether to use it to later predict, which in this case is very important to predict stock prices.
- **Data Preprocessing**: Uses pandas for data manipulation and preprocessing to prepare the dataset for training.
- **Visualization**: Leverages matplotlib to visualize the predictions made by the model and compare them to the real stock prices at the various dates that it is fed. 

## Dataset
The dataset I used for this model was from the yahoo finance website. The model takes the historical data of the stock it is given starting from 2010 all the way up until the current day in order to accurately predict the following days closing price. 

