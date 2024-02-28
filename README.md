# Logistic_Regression_Model

This model is built to predict the class of the datapoints to which it belongs, in specific the dataset is having attributes of a person like pregnancy, blood pressure,....... for women
Given the attributes we should build a model to predict the given person is diabetic or non-diabetic 
To solve this real world prediction model we use Logistic Regression.


Pre-Processing done on Dataset 
* Adding column name for dataset, as it was missing  
* There were no null values
* There were few outliers replaced them with median of their column
* Splitted Dataframe into two parts, i.e Test and Train dataset

By using the Logistic Regression the accuracy of the model was 78%, this could have performed well with more number of datapoints for a women with diabetes
class wise almost 90% accuracy for non-diabetics women, where as 60% accuracy for diabetic women.
