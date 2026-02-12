# Model Card



##### Intended use: 

The intended use for this model is to predict a student's exam score (a continuous value from 0 to 100) given factors such as their demographics, academic information such as the hours they have spent studying, and details about their lifestyle.



##### Metrics:

We used Mean Absolute Error (MAE) to evaluate our model(s) in this lab. MAE represents the average error between actual and predicted value, and our goal was to find the model and parameters that would minimize this value.



##### Limitations:

Our data is artificial, and while it mirrors real-life cases, there are bound to be differences when compared to data from real students. The synthetic data may have biases that would not be present in real-life data. In addition, the data may not represent all real-world cases and therefore the model may fail to predict grades accurately for those edge cases.



##### Risks:

There is a risk of our model overfitting/having bad generalization due to a large amount of categories in our data such as the specific academic program the student is in. There is also a leakage risk as student\_id is one of the features in the data (which we remove as part of our preprocessing).

