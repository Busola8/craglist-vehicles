# craglist-vehicles
# Week 4 Project

## Description
Using the Craigslist Vehicles Dataset available on Kaggle (https://www.kaggle.com/datasets/mbaabuharun/craigslist-vehicles), we'd like you to create a Time-Series Model following the approach outlined below. <br> <br>

## Key Steps
- Start by addressing missing values in the dataset. You can handle this by filling in missing values with the median for numerical columns and the mode for categorical columns.
- Ensure that the data types of the columns are appropriate. Specifically, make sure to convert the 'posting_date' column to a datetime data type.
- Utilize the 'posting_date' column to create a datetime index for the dataset. This will facilitate the analysis of temporal patterns.
- With clean data, explore it using various visualizations and statistical analysis techniques. This step is crucial for understanding temporal patterns, identifying seasonal trends, and analyzing demand-supply dynamics by region and vehicle type.
- Build the time-series chart.
- Finally, create a GitHub Repository and push your work there, also document your process through each of the steps and demonstrate your understanding by implementing them on the dataset.

## Key Features

### Data Preparation
- Importing Libraries: Import necessary libraries for data analysis and visualization.
- Loading Data : Load the Craigslist Vehicles Dataset for analysis.
- Exploring Data: Perform initial data exploration to understand the dataset's structure and contents.
- Checking for missing values: Identify and handle missing data by filling in missing values with the median for numerical columns and the mode for categorical columns.
- Imputing missing values for both numerical and categorical columns in dataset:  Implement missing data imputation for both numerical and categorical columns in the dataset.
- Correcting Datatypes: Ensure that the data types of the columns are appropriate, especially converting the 'posting_date' column to a datetime data type.
- Setting DataFrame Index: Use the 'posting_date' column to create a datetime index for the dataset, facilitating the analysis of temporal patterns.
- Remove Redundant Columns: Remove any redundant columns that do not contribute to the analysis.

### Exploratory Data Analysis
- Univariate Distributions: Explore individual feature distributions through visualizations and statistical analysis.
- Bivariate & Multivariate Distributions: Investigate relationships between variables and multivariate patterns to uncover insights about the dataset.

## Results and Findings
1. Analysis of the dataset reveals the majority of listings are for vehicles in good condition, followed by excellent and like new condition.
1. White is the most common vehicle paint color, while purple is the least common.
1. Popular car manufacturers, according to the word cloud, include Toyota, Chevrolet, and Ford.
1. Gas is the most common fuel type, followed by diesel and other fuels.
1. Most vehicles are full-size, followed by mid-size, compact, and sub-compact.
1. Automatic transmission is the most prevalent, followed by manual and other transmission types.
1. The dataset's most popular regions for vehicle listings are Columbus and Jacksonville.
1. The frequency of years increases steadily from 1900 to 2020, with a sharp increase around 2000, suggesting more recent data.
1. According to the word cloud, California, Florida, and Texas are the most popular states.
1. Diesel fuel is the most expensive, followed by other fuels, hybrids, and electric. Gas is the least expensive.
1. Vehicles with a “clean” title status have a significantly higher average price.
1. The highest number of cars posted for sale are sedans, followed by SUVs and pickups. Buses and offroad vehicles have the lowest number of listings.
1. The average price of cars posted for sale by vehicle type is highest for pickup trucks and lowest for minivans.
1. Price fluctuation over time shows a general decrease in prices with some peaks and valleys.
1. Vehicle prices have fluctuated over the years, with a sharp increase in the year 2000.

## Contributing
Contributions are welcome! If you would like to contribute to the project, feel free to reach out to me.

## Contact
For any questions or inquiries, please contact 	Busolaolusolape@gmail.com
