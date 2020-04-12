# Citibike-Ride-Duration-Neural-Network
## Key points in this project:
 - **Purpose**: Build a model that predicts bike ride duration with minimal error while operating within the limits of computing power. 
 - **Framework**: The modeling framework for this work is very simple and the target can be directly modeled. 
 - **Randomness**: The predictive variables in the dataset to be predicted and evaluated were chosed subjectively based on relevance to the outcome variable. 

## Key Strategies
- **Restrict the training data.** First restricted outcome variable of the tripduration to be from 1 minute to 1 hour, because less than 1 minute possibly means that the rider just tried on the bicycle and did not even take any ride, and more than 1 hour possibly means that the rider forgot to lock out the bicycle, which are all bad data to analyze. 

## Model
The model used in this work is a Linear Regression Model 

## Things I learned:

* Think the problem from a grand view, using different strategies to define the target and built up modeling framework.

## Things could have done better.

* It would be good if I could try other smoothing techniques except for spline.
