# Stroke data
## Finding stroke data

**Author**: Jeremy McCleary

### Business problem:

Predicting stroke data


### Data:
Predicting stroke data based on other health issues


## Methods
- I decided when cleaning the data to remove the,'id','gender','ever_married','work_type','Residence_type', columns from the data seeing as they didnt specifically pertain to the actual target itself(stroke or not having a stroke).
- Training, testing, and splitting the data and also making all columns with data that was having objects to numerical to make it easier for my model to run through the data.



#### Smoking status and stroke data
/content/ax_smoking_status.png

> This shows the stroke data for smokers, non smokers, people who formerly smoked, and unknown smokers

#### Glucose level and stroke data
/content/ax_glucose_level.png

>This shows the data for people who have a stroke with higher glucose levels

## My final model would be the logistic regression model with PCA applied
This model will help detect both true positives and true negatives. It has a 71% rate on detecting true positives and a 75% chance of detecting true negatives. Both are not perfect but it is a very well tuned model with the metrics on the confusion metrics report.

## Recommendations: Get more patients data

With more data it would help the results get better because it would be learning more and more data as it goes on further.


### For further information


For any additional questions, please contact **mcclearyjeremy94@gmail.com**
