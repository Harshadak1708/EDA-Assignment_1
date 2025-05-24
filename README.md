# 1. Assignment Title:
## 🚗 Car-Data-Exploratory-Analysis

# 2. Brief Overview:
This repository contains an in-depth Exploratory Data Analysis (EDA) performed on a used car sales dataset (car_data.csv). The assignment aims to understand the dataset's characteristics, identify patterns, uncover relationships between features, detect anomalies, and derive valuable insights that can inform future data modeling tasks, such as price prediction.

# 3. Technologies Used:
Python
Pandas (for data manipulation and analysis)
NumPy (for numerical operations)
Jupyter Notebook (for interactive development and documentation)

# 4. Dataset:
The dataset used for this analysis is car_data.csv. It contains information about various used cars, including their selling price, present price, kilometers driven, fuel type, seller type, transmission, and more.

# 5. Features & Analysis Covered:
## Dataset Overview:
Determined the total number of rows and columns.
Identified data types for each column.
## Data Cleaning:
Checked for and quantified missing values across the dataset.
Identified and counted duplicate records.
## Categorical Feature Analysis:
Explored unique values within Fuel_Type, Seller_Type, and Transmission columns.
Counted the number of cars for each Fuel_Type.
Analyzed the distribution of cars by Seller_Type (individual vs. dealers).
Identified unique combinations of Fuel_Type, Seller_Type, and Transmission.
## Price Analysis:
Calculated average, maximum, and minimum Selling_Price.
Determined average Selling_Price by Fuel_Type.
Calculated average Selling_Price by Transmission type.
Identified the average Selling_Price for each car model.
Investigated the average difference between Present_Price and Selling_Price.
Identified Seller_Type with the highest average Selling_Price.
Checked for instances where Selling_Price is greater than Present_Price.
Identified the top 5 most expensive cars in the dataset.
Determined which car has the highest Present_Price.
## Vehicle Characteristics & Usage:
Identified the car model that appears most frequently.
Determined the range of manufacturing years (min and max Year).
Calculated the average Selling_Price grouped by Year.
Identified the most common number of previous owners.
Quantified cars with more than one previous owner.
Calculated the average Selling_Price for cars with more than 2 previous owners.
Counted cars sold with exactly 0 previous owners.
Calculated the average Kms_Driven.
Determined the highest and lowest Kms_Driven for each fuel type.
Counted cars manufactured before 2010.
Identified the year with the highest number of car listings.
## Correlation Analysis:
Calculated the correlation between Selling_Price, Present_Price, and Kms_Driven.
## Percentage Analysis:
Determined the percentage of cars using diesel, petrol, and CNG fuel types.


