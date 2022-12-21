# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### KIBRU TEMESGEN

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: It needed to have a time stampe so that each prediction is uniquely identified. The submission.csv file was helpful in that regard. Since count cannot be negative, it was necessary to convert the negative values to zero.

### What was the top ranked model that performed?
TODO: KNeighborsDist

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: I was able to visualize the frequency distribution of diffrent features. I added the hour as an aditional feature because it varies a lot through out the dataset.

### How much better did your model preform after adding additional features and why do you think that is?
TODO:from 1.8 to 0.49 which is a huge leap. The additional feature such as month, day, hour, and year are important features whose effect should be accounted for independently not as a whole datetime feature.

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: it has performed better than the previous one

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: optimizing hyperparameters so that I can try multiple architectures.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
I have prepared a table at the end of the jupyter notebook file.
### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: I trained each of the three models multiple types, and for the purpose of viewing the kaggle score, I submitted my score multiple times. The kaggle score I used in the report if the best score for each of the 3 models.
