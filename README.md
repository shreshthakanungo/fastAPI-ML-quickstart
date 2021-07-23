This project is the “Boston house pricing” project. In this project I have created an application which uses  the Random Forest Regressor from the scikit-learn package. 
I have built this application which receives data in the form of HTTP request and returns a HTTP response. This application communicates through an API. Here I have used FastAPI, 
which is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ . This application will run in 3 steps :
i.   Process the input
ii.  Make the predictions
iii. Process the output and return it to the user.

The task here was to build a good accuracy ML model which gives at least 70% accuracy in finding the prices of house in that area based on the different features such as the no.of
rooms in a house, pupil teacher ratio in the area, crime in the area, age, tax, weighted distance to 5 employment centers and accessibility to radial highways etc.

Firstly I created my own Virtual Machine and uploaded the project dependencies which are several python libraries. Now loadinf the dataset and apply data cleaning methods, first 
I applied feature engineering to find the relationship between the different features which affect the prices of houses in the area. Such as no. of rooms is directly proportional 
to the prices. Same as increase in crime rate decreases the price of the house in that area. As this was a supervised learning model, I created a Random Forest Regressor which 
takes these features and generates a prediction. 

I achieved a good accuracy of 72.8% in this project. I also used new libraries such as FastAPI and created a pipeline, which makes my project prone to errors and highly
reliable. At last I created a Docker container and deployed it.
