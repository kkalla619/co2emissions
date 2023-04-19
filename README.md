# Exploring Trend in CO2 Emissions of Top 10 emitters Over 50 Years
## Introduction 
The purpose of this project is to analyze trends in CO2 emissions over the last 50 years using Python. The project uses a dataset of greenhouse gas emissions from Our World in Data to describe how the emission levels of the current top 10 CO2 emitters have changed over the last 50 years. The analysis includes data preprocessing, filtering of top emitters, grouping of data by year and country, and plotting of time series graphs to visualize the trends.

The results of the analysis indicate that while the total CO2 emissions have increased globally, the top 10 emitters have had varying levels of emissions over the years. Some countries have had a steady increase, while others have had fluctuations and even a decline in emissions. 

Overall, this project provides insights into the changing patterns of CO2 emissions among the top 10 emitters over time, which can help inform discussions and policies related to climate change mitigation.


## Requirements
Software used to run the code for this project was Google Colab
## Data 
Data: https://raw.githubusercontent.com/owid/co2-data/master/owid-co2-data.csv
data is obtained from the Our World in Data and was downloaded on 3/29/2023 at 1:59pm 
## Data Processing Section
In the data processing step, the raw data was read into a Pandas DataFrame in Google Colab. The data was then cleaned by removing unnecessary columns, checking for missing values and filling them appropriately. The country names were standardized to ensure consistency across the dataset. The data was then exported to a clean csv file for further analysis.
These steps were performed using Python in a Google Colab notebook. The resulting clean CSV file was used in subsequent analysis of greenhouse gas emissions trends over time.

## Author 
This file was created, documented, and computed by Keerthana Kalla
## License 
All materials in this repository are licensed under the Creative Commons Attribution 4.0 International License. This means that others are free to use, share, and adapt the materials as long as proper attribution is given
