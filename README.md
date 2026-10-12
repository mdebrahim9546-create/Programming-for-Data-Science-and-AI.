# Programming-for-Data-Science-and-AI.
My first data science project using Python
# Bank Marketing Data Analysis
### Understanding Customer Balance and Marketing Campaigns

## About the Project

This project was completed as part of the **Programming for Data Science and AI** course at Tokyo International University.

The project uses bank marketing data to explore the relationship between customers' age groups and their account balances. The goal is to understand how average account balance differs across age groups and consider which group the bank could target for its marketing campaign.

## Research Question

1. Does average account balance differ between customers in three age groups?
2. Which age group should the bank target for its marketing campaign?

## Hypothesis

Average account balance differs across the three age groups, and the Adult group should be targeted for the campaign.

## Dataset

The project uses the Bank Marketing dataset from Hugging Face.

Dataset source: https://huggingface.co/datasets/cestwc/bank-marketing

### Key Variables

- **Age:** Customer's age in years.
- **Job:** Customer's job category.
- **Balance:** Customer's account balance.
- **Duration:** Length of the last marketing phone call, in seconds.
- **Campaign:** Number of contacts made with the customer during the campaign.

## Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Quality Checks

Before analyzing the data, I checked:

- Missing values
- Duplicate rows
- Data types
- Minimum and maximum values of numerical variables
- Unique values in each column

These checks helped me understand the dataset before creating the visualizations.

## Methodology

I divided customers into three age groups:

- **Young:** Under 25 years old
- **Adult:** 25–45 years old
- **Old:** Over 45 years old

I then calculated the average account balance for each age group and created two visualizations.

### 1. Bar Graph: Average Balance by Age Group

The bar graph compares the average account balance across the three age groups. It helps identify which group has the highest and lowest average balance.

### 2. Scatter Plot: Customer Account Balance by Age

The scatter plot shows individual customers' ages and account balances. Different colors represent the three age groups. It helps visualize variation in account balances and the relationship between age and balance.

## Key Findings

The analysis showed that:

- Average account balance differed across the age groups.
- The Old group had a higher average account balance than the Young group.
- Individual customers had different account balances, including some negative balances.
- Based on average account balance alone, the Old group may be worth considering for the bank's campaign.

A higher average balance does not necessarily mean that a group is more likely to respond to a marketing campaign.

## Limitations

- The analysis identifies patterns but does not prove cause and effect.
- Other factors, such as job category and income, may also be related to account balance.
- The age groups were defined for this analysis, and different age ranges might produce different results.
- No statistical significance test was performed.
- The analysis did not directly measure customers' likelihood of responding to the campaign.

## What I Learned

Through this project, I practised using Python to inspect data, check data quality, group customers, calculate averages, and create visualizations. I also learned that data analysis can help explore business questions, but findings should be interpreted carefully.

## Project File

The Jupyter Notebook contains the code, data checks, visualizations, and analysis for this project.
