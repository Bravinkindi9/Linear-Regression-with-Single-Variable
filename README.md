## Problem Statement

You are a data scientist / AI engineer at a meteorological consulting firm. You have been provided with a dataset named **"weather_data.csv"**, which includes detailed records of various weather conditions. The dataset comprises the following columns:

- **`hours_sunlight:`** The total number of hours of sunlight received in a day.
- **`humidity_level:`** The humidity level as a percentage.
- **`daily_temperature:`** The temperature recorded at the end of the day in degrees Celsius.

Your task is to use this dataset to build a linear regression model to predict the daily temperature based on the hours of sunlight and humidity level.

### Task 1: Train a Linear Regression with Single Variable

1. Import the data from the "weather_data.csv" file and store it in a variable df.
2. Display the number of rows and columns in the dataset.
3. Display the first few rows of the dataset to get an overview.
4. Create a Linear Regression model and fit it using only the `hours_sunlight` variable to predict `daily_temperature`.
5. Print the model's coefficient and intercept.
6. Predict the daily temperature with the following hours of sunlight:
   - 5 hours
   - 8 hours
   - 12 hours
