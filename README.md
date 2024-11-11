# Prodigy InfoTech Data Science Internship Task 2:
## Data Cleaning and Exploratory Data Analysis (EDA) on Titanic Dataset
![image](https://github.com/user-attachments/assets/f0b30916-d5c6-4a2f-81bf-e3541df51ce9)


Welcome to my submission for Task 2 of the Data Science Internship at Prodigy Infotech. This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The primary objective is to explore relationships between variables and identify patterns and trends in the data.

## Table of Contents
- [Overview](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/blob/main/README.md#overview)
- [Dataset](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/blob/main/README.md#dataset)
- Steps Involved
   - [Data Cleaning](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#1-data-cleaning)
   - [Exploratory Data Analysis (EDA)](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#2-exploratory-data-analysis-eda)
- [Requirements](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#requirements)
- [Usage](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#usage)
- [Results](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#results)
- [References](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/tree/main?tab=readme-ov-file#references)

## Overview
The Titanic dataset, widely available on Kaggle, includes details of passengers aboard the Titanic, such as their age, gender, fare, class, and whether they survived. This project aims to clean the dataset by handling missing values, removing duplicates, and then using visualizations to explore key patterns.

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/test-file?select=tested.csv)
- Description: This dataset includes various features of Titanic passengers such as:
  
   - `Age`: The age of the passenger.
   - `Fare`: The amount paid for the ticket.
   - `Sex`: Gender of the passenger.
   - `Embarked`: Port of embarkation.
   - `Cabin`: Cabin number or unknown if missing.
   - `Survived`: Whether the passenger survived the incident.

## Project Workflow
### 1. Data Cleaning
Data cleaning ensures the dataset is ready for analysis. The following steps are applied:

- **Handling Missing Values:**
  
   - The missing values in the `Embarked` column are removed by dropping rows where `Embarked` is missing.
   - Missing values in the `Cabin` column are filled with the string `"Unknown"`.
   - Missing values in the `Age` column are replaced with the mean age of all passengers.
     
- **Removing Duplicates:** Duplicates in the dataset are identified and removed.
  
- **Verifying Nulls and Duplicates:** After cleaning, the dataset is checked for any remaining missing values or duplicates.

### 2. Exploratory Data Analysis (EDA)
EDA is used to understand the dataset better through visualizations and summary statistics. Key visualizations include:

- **Age Distribution:** A histogram with a KDE curve is created to visualize the distribution of passengers' ages.
- **Gender Distribution:** A count plot shows the number of male and female passengers.
- **Age vs. Fare:** A scatter plot displays the relationship between passenger age and fare, with color indicating age.
  

## Requirements
- Python 3.x
- Jupyter Notebook or any Python IDE
- Libraries:
   - Pandas
   - Matplotlib
   - Seaborn


## Usage
1. Clone this repository or download the files.
2. Download the dataset from Titanic Dataset (Kaggle).
3. Place the [`tested.csv`](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/blob/main/tested.csv) file in the project directory.
4. Run the Python code in [`Titanic.ipynb`](https://github.com/Priyanxxhiiii/PRODIGY_DS_02/blob/main/Titanic.ipynb) (Jupyter Notebook) or as a Python script to clean the data and perform EDA.


## Results
This analysis yields key insights such as:

- **Age Distribution:** Understanding the distribution of ages among passengers.
- **Survival by Gender:** Exploring the number of male and female passengers.
- **Relationship Between Age and Fare:** Visualizing how passenger age correlates with fare.
  
These findings lay the groundwork for further analysis or predictive modeling, such as survival prediction based on various factors.


## References
- [Titanic Dataset (Kaggle)](https://www.kaggle.com/datasets/brendan45774/test-file?select=tested.csv)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
