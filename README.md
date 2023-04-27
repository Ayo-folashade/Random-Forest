# Random Forest Regression Model for House Pricing Prediction
This project implements a random forest regression model for predicting house prices based on several features, such as lot area, year built, and number of bedrooms and bathrooms. The dataset used for this project is the House Prices: (https://www.kaggle.com/code/ajaypalsinghlo/home-data-for-ml-course-housing-prices/data?select=train.csv).

## Getting Started
To use this model, you need to have Python 3 and the following libraries installed:

- pandas
- scikit-learn
You can install them using pip: pip install pandas scikit-learn

You also need to download the train.csv file from Kaggle and save it in the same directory as the script.

## Usage
To use the model, simply run the random_forests.ipynb:

## random_forests.ipynb

The script will split the data into training and validation sets, fit a random forest regression model to the training data, and calculate the mean absolute error of the model on the validation data. The result will be printed to the console.
 
 ## Result
The Validation MAE (Mean Absolute Error) of the Random Forest Model on the validation data is 21857. This means that on average, the predictions made by the model are off by around $21857 from the actual sale price. A lower MAE indicates better accuracy, so there may be room for improvement in the model.
