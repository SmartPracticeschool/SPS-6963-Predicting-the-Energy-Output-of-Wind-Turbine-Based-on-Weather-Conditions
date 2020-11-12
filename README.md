# Predicting Energy Output of Wind Turbine based on the Weather Conditions

Description of Project

Wind energy plays an increasing role in the supply of energy world-wide. The energy output of a wind farm is highly dependent on the wind conditions present at its site. If the output can be predicted more accurately, energy suppliers can coordinate the collaborative production of different energy sources more efficiently to avoid costly overproduction.
Solution Offered through this project

I analyzed the data for a Windmill Farm and extracted the weather parameters (assuming other physical conditions like weight of blades, height of windmill to be same etc) that affect power generation the most. Then we prepared an ML model taking the obtained features in consideration, using Boosted Regressor Tree Model. Then for provinding solution quicker to the end-user, we made an Android app to obtain power predictions of next 72 hours on hourly basis in single click.
Software Development Life Cycle(SDLC) Model Used

I used Iterative Waterfall SDLC model in making of this software. For the development of ML Model we tested it using IBM Watson Studio to get maximum accuracy. For developing the apps, in the initial phase all the requirements were fixed, then design of app was prepared and finally it was coded following Waterfall Model. Finally the app is deployed on Heroku server for public use.
Technology Stack Used

Jupyter Notebook (Python3) for Data Preprocessing, IBM Watson Studio for ML Model Testing and Prototyping, Python3 for ML model development and Flutter for front-end app development and Flask for back-end and integration with the model.
Other Reference

Weather Underground, Kaggle for Windfarm data, Climacell API, Heroku for hosting server
Climacell API key has been removed from app.py

# Wenergy

A Flutter application for predicting the theoretical power output of the wind turbine.
We have built a forecasting model for predicting the wind speed based on which the power 
output of the turbine is calculated.
One hour forecast is predicted in 1.25 minutes intervals.
Hourly forecast is also predicted.
The current weather of a particular location is also made available in the Weather.
