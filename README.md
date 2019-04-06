Link to mybinder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cba-dat-sem4-python-group/Assignment-8/master?filepath=Assignment-8.ipynb)

# Assignment-8

https://think.cs.vt.edu/corgis/csv/cars/cars.html

## Exercises

### Download the data

- Programatically download the data from the above link.
- Import the data into a Pandas dataframe.
- Show the head of the Pandas dataframe.

### Linear regression

- Perform linear regression on the downloaded dataset, where `y=Highway mpg` and `x=Horsepower`.
- What is the coefficient (slope) of your model? What does this number mean?
- According to your model, what is `y` when `x=2000`.
- Show the regression line on a scatterplot with the other datapoints.

### Classification

- Using `sklearn` create a classifier that can predict the make of a car, based on provided features. The following features should be included:
  - `City mpg`
  - `Highway mpg`
  - `Height`
  - `Width`
  - `Length`
  - `Horsepower`
  - `Year`
- Show the decisiontree of your model.
- Use your model to predict the make of a car.

## Review questions 

1. Did the student programatically download and import the data?
2. Did the student correctly display the regression line in a graph`?
3. Did the student find the coefficient of the line, and reflect on its meaning?
4. Did the student correctly provide their classification model with imported data?
