# :car: Car-Price-Prediction

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/dataset-cover.jpg)

This dataset was taken from the Kaggle community, at this link: https://www.kaggle.com/hellbuoy/car-price-prediction

The Business Goal of this problem is to model the price of cars using the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. Using regression algorithms, the model with the best evaluation is when using Random Forest Regressor, with 89,76% accuracy (R2 Score). When the Cross-Validation technique is applied, the model's accuracy reuces, reaching 73,68%. However, Random Forest Regressor continues to be the model with the greatest precision, compared to other machine learning models. This means that the model is 89,76% better than if we took the average of all values, as can be seen in the graph below, showing the result of the first hundred instances.

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/graphics.jpg)

In addition to the Business Goal, I tried to answer 5 business questions:

1 - Car prices are around how many dollars? Most prices are concentrated between 5000.00 and 10000.00

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/1.jpg)  
  
2 - What kind of car appears most in the dataset? The sedan-type cars are the most popular.

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/2.jpg)    
  
3 - What type of fuel is most used? Gasoline is the most used fuel, with 90.0%, while diesel is used in 10.0% of cases.

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/3.jpg)  

4 - What are the most common engine power? The distribution shows that engines with power between 60 and 120 hp are the most common.

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/4.jpg)  

5 - What is the most common insurance risk classification? A zero (0) rating is the most common among all insurance risk ratings. The assigned insurance risk rating is a value ranging from +3 (indicates that the car is risky) to -3 (which is probably very safe).

![alt text](https://github.com/Daniel-RPS/Car-Price-Prediction/blob/main/5.jpg)  
