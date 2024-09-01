# Covid_19_project
### Project Overview
##### This project focuses on analyzing COVID-19 data to extract meaningful insights. The data contains information on confirmed cases, deaths, and recoveries across various regions and states. The analysis aims to provide a better understanding of the spread and impact of the virus during the period covered by the dataset.

### Dataset Information
#### The dataset consists of the following columns:

##### Date: The date of the reported data.
##### State: The state within the country where the data was collected.
##### Region: The region within the state where the data was collected.
##### Confirmed: The number of confirmed COVID-19 cases.
##### Deaths: The number of deaths due to COVID-19.
##### Recovered: The number of recovered cases from COVID-19.
### Analysis Steps
#### 1. Initial Data Exploration
##### df.head(): Displays the first few rows of the dataset.
##### df.tail(): Shows the last few rows of the dataset.
##### df.shape: Reveals the number of rows and columns in the dataset.
##### df.isnull(): Identifies missing values within the dataset.
##### df.isnull().sum(): Counts the number of missing values in each column.
##### df.notnull().sum(): Counts the number of non-missing values in each column.
##### sns.heatmap(df.isnull()): Visualizes missing data in the dataset using a heatmap.
### 2. Questions Answered
##### Q1: What is the number of confirmed, death, and recovered cases in each region?
##### Q2: How do we remove all records where confirmed cases are less than 10?
##### Q3: In which regions were the maximum number of confirmed cases recorded?
##### Q4: How many Confirmed, Death, and Recovered cases were reported from Kenya till the 29th of April 2020?
