# Abstract

The project is about guessing the income of selected people in the dataset using the Machine Learning models. This project is divided into 4 parts:
1. Exploring Data.
2. Cleaning.
3. Visualization.
4. Modeling.

## Exploring Data:
In this part, we went through the data to have an idea about the content of the dataset and what needs to be cleaned. 

## Cleaning:
We used Pandas and Numpy to clean the data; the cleaning process can be summarized in the following points:
1. Reformatting columns headers.
2. Removing rows with ```?``` character.
3. Removing extra space was available as a prefix of each string value in the dataset.
4. Removing one column ```fnlwgt``` that contains meaningless information. 

## Visualizaion:
In this section we used ```matplotlib``` and ```seaborn``` to visualize the answers of three questions:
1. What is the age average for each gender of the individuals with the income over 50K and at most 50K?
2. In which work class both genders, who make over 50K or 50K or less a year, are mostly working in?
3. Do the Capital Gain and the Capital Loss data has any relationship with the income given values?

## Modeling:
In the modeling section, we did a comparison between 6 classification models. The models that are chosen to this comparison are: ```Logistic Regression```, ```Ada Boost Classifier```, ```Gaussian NB```, ```Decision Tree Classifier```, ```Gradient Boosting Classifier```, and ```Random Forest Classifier```.
To compare we used:
1. The confusion matrix.
2. The classification report.
3. The accuracy value.
4. The MSE value. 
