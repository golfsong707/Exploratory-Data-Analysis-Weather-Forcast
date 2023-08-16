# Exploratory Data Analysis with Pandas:Weather Forcast dataset analysis.
This repository contains Python code for data analysis using the Pandas library. It demonstrates various operations on a weather dataset to showcase the capabilities of Pandas for data manipulation and analysis.This Python code that involves working with the Pandas library for data analysis tasks on weather dataset. The code includes various tasks such as data filtering, indexing, extracting specific columns, and performing comparisons.

Follow these instructions to get a copy of the project and run the code on your local machine.

### Prerequisites

You need to have Python and the required libraries installed. You can install the required libraries using the following command:


## Code 

### 1. Loading and Preprocessing Data

- Import the necessary libraries (Pandas, Numpy).
- Load the weather dataset using `pd.read_csv`.
- Convert the 'Date/Time' column to a datetime data type using `pd.to_datetime`.

### 2. Exploring the Dataset

- Use `head()` to display the first few rows of the dataset.
- Display information about the DataFrame using `info()`.

### 3. Data Filtering and Analysis

- Filter data based on specific conditions using boolean indexing.
- Count unique values in the 'Weather' column using `nunique()` and `value_counts()`.

### 4. Extracting Specific Data

- Extract specific columns using single brackets (`['col_name']`).
- Extract specific rows using integer-based indexing (`iloc`) and label-based indexing (`loc`).

### 5. Data Visualization

- Not included in this code snippet, but you can use libraries like Matplotlib or Seaborn to visualize the data.

## Contributing

Feel free to contribute improvements or additional analyses to this repository. Fork the repository, make your changes, and submit a pull request.

## Authors

- Your Name

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Here's a summary of what each part of your code does:

You import the necessary libraries, pandas and numpy.
You read a CSV file named "weather_2012.csv" using Pandas, and store the data in a DataFrame named weather_df.
## You perform data cleaning and manipulation:
Convert the 'Date/Time' column to a datetime data type.
Display information about the DataFrame using the info() method.
## You demonstrate data slicing and filtering:
Display the first few rows of the DataFrame.
Extract the 'Date/Time' column.
Extract specific rows and columns using slicing and indexing.
Filter data based on certain conditions, such as wind speed and weather conditions.
## You perform tasks related to data analysis and filtering:
Display unique values in the 'Weather' column.
Count occurrences of each weather condition using the value_counts() method.
## You demonstrate different ways to access columns and rows:
Use label-based indexing to access specific rows and columns.
Use integer-based indexing with the iloc method.
You compare two methods of accessing columns and rows to check if they yield the same results.
You show how to use the loc property to filter and access rows and columns based on labels.
You further demonstrate filtering by snow-related weather conditions.
You perform a comparison between wind speed and visibility conditions using boolean filtering.

