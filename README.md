# Exploratory Data Analysis with Pandas:Weather Forcast dataset analysis.
This repository contains Python code for data analysis using the Pandas library. It demonstrates various operations on a weather dataset to showcase the capabilities of Pandas for data manipulation and analysis.This Python code that involves working with the Pandas library for data analysis tasks on weather dataset. The code includes various tasks such as data filtering, indexing, extracting specific columns, and performing comparisons.

Follow these instructions to get a copy of the project and run the code on your local machine.

### Prerequisites
Python installed on your system
Required libraries: pandas

### Analysis Steps
To run the analysis, make sure you have Python and the pandas library installed. You can install pandas using the following command: pip install pandas

Place the apple_products.csv file in the same directory as the Jupyter Notebook or Python script that you'll use for analysis.


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

## Authors note:
To further this analysis, additional analysis or visualization can be perform based on the new  requirements needed.

