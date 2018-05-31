# PIMA Indian Diabetes Diagnosis #

Contributors: Calvin Wang, Mary Zhao

## Inspiration ## 

Can we train a machine learning model to accurately predict whether or not a patient in the dataset has diabetes or not. Mary is a pre-med student at UCSB while Calvin is a CS student pursuing deep learning. We will be attempting to combine our interests to tackle a Kaggle challenge. 

## Data ## 

We acquired our data from Kaggle. 
https://www.kaggle.com/uciml/pima-indians-diabetes-database

## Exploratory Analysis ## 

## Training ## 

## Results ## 

- 1st round training: We chose to ignore all instances in the dataset with missing values in this round. After training for 40 epochs and a batch size of 5, our model performs at 69.6% accuracy for diabetes diagnosis. 

- 2nd round training: We kept the instances with missing values in this round by filling in the average values with the means of the feature. Although this is not the most sophisticated way of data augmentation, this significantly brings up our dataset size. With this, we were able to reach a 77.1% accuracy for diabetes diagnosis on logistic regression. 
