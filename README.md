# House Price Prediction Using Keras
 
 In this repository, I have tried to predict house prices using a neural network model in Keras.
 <br/>
 <br/>
 # Data
 This project uses a customized housing price data with the following features:<br/>
 Number of rows: 5000<br/>
 Number of columns :7<br/>
 Features:<br/>
 
 - Year of sale of the house
 - Age of the house at the time of sale
 - Distance from the city centre
 - Number of stores in the locality
 - Latitude
 - Longitude
 <br/>
 
# Goal
 
To predict the housing sale price of a particular house using Neural Networks in Keras and make use of "EarlyStopping" and "History Callback" feature in neural networks
<br/>
<br/>

# Model

The model that I have implemented has the following features:

<br/>

- Dense Hidden Layer with 10 neurons (activation = relu)
- Dense Hidden Layer with 50 neurons (activation = relu)
- Dense Hidden Layer with 30 neurons (activation = relu)
- Optimizer = "Adam"
- Loss = Mean Squared Error

# Tracking Metric

For this model, I have tracked the validation loss as a parameter for which no more training is required at a patience level of 5 epochs





 
