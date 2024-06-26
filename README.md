# New York City Taxi Fare Prediction
![header](https://github.com/JamesSuryaPutra/New-York-City-Taxi-Fare-Prediction/assets/155945814/68f87339-8fb6-4cf7-806b-11fa222a115c)

# Description
In this playground competition, hosted in partnership with Google Cloud and Coursera, you are tasked with predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. While you can get a basic estimate based on just the distance between the two points, this will result in an RMSE of $5-$8, depending on the model used (see the starter code for an example of this approach in Kernels). Your challenge is to do better than this using Machine Learning techniques!

To learn how to handle large datasets with ease and solve this problem using TensorFlow, consider taking the Machine Learning with TensorFlow on Google Cloud Platform specialization on Coursera; the taxi fare problem is one of several real-world problems that are used as case studies in the series of courses. To make this easier, head to Coursera.org/NEXTextended to claim this specialization for free for the first month!

# Evaluation
The evaluation metric for this competition is the root mean-squared error or RMSE. RMSE measures the difference between the predictions of a model, and the corresponding ground truth. A large RMSE is equivalent to a large average error, so smaller values of RMSE are better. One nice property of RMSE is that the error is given in the units being measured, so you can tell very directly how incorrect the model might be on unseen data.

RMSE is given by:
![rmse_0](https://github.com/JamesSuryaPutra/New-York-City-Taxi-Fare-Prediction/assets/155945814/aebf99cb-d3b4-49ee-aad5-518a24b3cb71)

where yi is the ith observation and y^i is the prediction for that observation. 

## Example 1
Suppose we have one observation, with an actual value of 12.5 and a prediction of 12.5 (good job!). The RMSE will be:
![rmse_1](https://github.com/JamesSuryaPutra/New-York-City-Taxi-Fare-Prediction/assets/155945814/bff371c8-8999-4797-bd84-5ed5952565ba)

## Example 2
We'll add another data point. Your prediction for the second data point is 11.0 and the actual value is 14.0. The RMSE will be:
![rmse_2](https://github.com/JamesSuryaPutra/New-York-City-Taxi-Fare-Prediction/assets/155945814/5ca94c11-b234-4f3d-9e65-3b6e8fb68a47)

