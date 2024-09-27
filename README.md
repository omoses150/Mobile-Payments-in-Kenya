# MOBILE MONEY PAYMENTS IN KENYA

[Colab](https://colab.research.google.com/drive/1HDccJ-hdiFymSoiiS-X0kyW18F4QtHs3?usp=sharing)

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion/ Findings](#conclusion-findings)
- [Recommendation](#recommendation)
- [Limitation](#limitation)
- [References](#references)

## Project Overview
This project is an analysis of mobile payments in Kenya from inception in 2007 to 2003 giving a clear trend over the years in terms of cash transacted in value and volumes, mobile money accounts registered and active agents recruited.

## Objectives
1. To determine the value of the agent cash in and cash out over the given time period.
2. To identify the total transactions done through the active agents over years.
3. To show whether an increase in registered mobile money accounts influence the transaction volumes and value.
4. To determine whether there is a significant relationship between active agents and transaction value and volumes.

## Data Sources
The primary dataset used for this analysis is the 'Mobile Payments.csv', a file containing detailed information about mobile payments in Kenya from 2007 to 2023, providing a rich source for analysis of mobile payments and trends.

### Key Data Features 
- Year: Annual fiscal year mobile money transactions occur in Kenya.
- Month: Monthly data for mobile money transactions.
- Total registered mobile money accounts: Number of users who have registered mobile money accounts.
- Total agent cash in cash out volume: Quantity of mobile money transactions as per records of mobile money agents. Mobile money agents are small mobile phone stores or retail locations—which allow users to deposit and withdraw in-person. Cash in represent deposits and cash out represent cash withdrawals.
- Total cash in cash out value: Monetary value of all mobile money transactions that occurred in Kenya from January 2007 to August 2023.

## Tools Used
Python has been used to preprocess the data, analyze and visualize the same.

## Data Preprocessing

I performed the following tasks to prepare the data for analysis and visualization:
1. Data loading and inspection.
2. Checking for and handling missing values incase of any.
3. Checking for and handling duplicates incase of any.
4. Formatting of year column to datetime, renaming to to date and extracting the year from date.

## Exploratory Data Analysis
### Multivariate Analysis
Analyzing the relationship amongst different parameters: 'Active Agents', 'Total Registered Mobile Money Accounts (Millions)', 'Total Agent Cash in Cash Out (Volume Million)', and 'Total Agent Cash in Cash Out (Value KSh billions)'.

Building a heatmap to show correlation- Whether there is a stong relationship amongst various numerical measures.

### Analysis Outcome
- There is a strong relationship among the numerical parameters in the dataset which include 'Active Agents', 'Total Registered Mobile Money Accounts (Millions)', 'Total Agent Cash in Cash Out (Volume Million)', and 'Total Agent Cash in Cash Out (Value KSh billions)'. This is because the values in the correlation heatmap are near one. This implies that increase in, for example, active agents automatically affects transaction volumes and values.

## Conclusion/ Findings
1. Generally there has been an inreasing trend in mobile money payments from active agents, registered mobile money accounts, transaction volumes and values.
2. We owe increase in transaction volumes and values to the increasing number of registered mobile money accounts every year.
3. Over the analysis period, 2022 recorded the highiest transaction volumes and value.
4. There is a direct relationship between the number of active agents and the transaction volumes and value.

## Recommendation
- Any mobile money company entering the Kenyan market need to invest in recruiting as many agents as possible to maximize on the transaction volumes and values.
- The agents need to be empowered in terms of trainings and the requisite resources to recruit many mobile money account holders who transition from minors to adults every year.

## Limitation
The data collected for the year 2023 is only for eight months hence giving a false impression of a decline. This could have been different had the data for the whole year 2023 
been considered.

## References
1. [Kaggle](https://www.kaggle.com/datasets?search=mobile+payments+in+kenya)
2. [Central Bank of Kenya Website](https://www.centralbank.go.ke/reports/cbk-reports-and-financial-statements/#)


