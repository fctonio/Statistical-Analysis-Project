<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Statistical-Analysis-Project
*Anton Neike*

*Data-ber-08-20, Berlin & 13/09/2020*

## Content
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

The goal of this project is to identify the most important features of houses that affect the sale prices. 

## Dataset

For this project, I used a dataset from Kaggle on Housing Prices. I downloaded the train.csv dataset and used statistical analysis skills to analyze this dataset. 
The Dataset can be downloaded from the following link: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data


## Workflow

- First: I read the data into a DataFrame<br>
- Second: I used basic pandas functions to familiarise myself with the data. (head(), shape, isnull().sum() ...)<br>
- Deleted all unnecessary columns.<br>
- wrote function to find the columns with a absolute correlation of at least 0.6. (I found 6 colums)<br>
- I then made:<br> 
-> an OLS model all six Columns and checked the statistical relevance.<br>
-> an OLS model with four of the six Columns since they had the same unit and that way we could compare them between each other and check the statistical relevance. (Square feet)<br>
-> an OLS model all with only the column with the biggest corrolation and checked the statistical relevance

## Organization

In the repository you will find several files and a Folder:<br>
<br>
1 - .gitignore -> To not push everything.<br>
2 - README.md -> That would be this beautiful file :P<br>
3 - statistical-analysis.ipynb -> The code and analysis of the Dataset<br>
4 - Data (Folder):<br>
    4.1 - train.csv -> <br>
    
## Links
[Repository](https://github.com/fctonio/Statistical-Analysis-Project)
