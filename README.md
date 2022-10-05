# SynchVR_Technical_Assessment

**Table of content**

- [Project Overview](#Project_Overview)
- [Installation](#installation)
- [Requirements](#Requirements)
- [Data](#data)
- [Notebooks](#notebooks)
- [PowerBI](#powerbi)
- [Summary_Findings](#Findings)
- [Key_Insights](#Insights)

## Project_Overview

This project aims to communicate findings revealed from the loan data at prosper using exploratory and explanatory data analysis. The project consists of different parts including pleriminarly wrangling and three types of analysis whereby we try to understand more the dataset and provide valuable insights.

## installation 
```
git clone https://github.com/skevin-dev/SynchVR_Technical_Assessment
cd synchVR_Technical_Assessment
jupyter notebook 
```

## Requirements

* pandas 
* numpy 
* Matplotlib
* Seaborn

## data

The dataset comes from Prosper Marketplace Inc., a company that makes loans to people. It includes 113,937 loans, each with 81 variables such as loan amount, borrower rate (or interest rate), current loan status, borrower income, employment status , and many more.

## Notebooks

> All the analysis and examples of implementation can be here in the form of .ipynb file

## PowerBI 

> This folder contains powerBI file containing different visualization. It also contains screenshots folder in case someone doesn't have powerbi 


## Findings

> Using univariate exploratory data analysis, histograms were used to analysis the distribution of nominal data. BorrowerAPR and BorrowerRate seem to have the same distribution and nearly normal distribution. Additionaly,Features like DelinquenciesLast7Years and StatedMonthlyIncome seems to be left-skewed. Bar charts were also used to understand qualitative columns. With ProsperRating (Alpha), we can see that "C" category outweighs others, whereby 4 is customer risk sccore with high values in the properscore columns. Borrow home owner status are quite balanced and those who are employed are the one with the most loan compared to the other employee job status.

> Bivariate analysis help us to adequately analysing the data using two variables. From pie and bar charts. We saw interesting findings from the dataset using different varibles. To begin with pie charts, we realized that AA which is the highest rating received the lowest loan while lowest rating(HR) received highest loan. Additionaly, we saw interesting insights from the relationship between loan status and prosperRating whereby C is the category with high current loan, while people in D have mostly completed their loans.

> Using FacetGrid, I provided multivariate plot which combines the two bar charts. The graph depicts relationship between three variables which are loan status, employment status and homeownership. As shown on the graph, people with home and employed are the one with high current loans whilst category with other and no homer are the most to complete the loan followed by full-time with home.

## Insights 

> From univariate analysis, we saw that being employed and own a home gives you the more chance to get a loan. From bivariate analysis, I saw that people with high prosper rating have a priveledge of lowest Borrower APR percentage.

> According to the findings, the more income you have, the more the company trusts you to have loans. Having a house and a job are also benefits of obtaining a loan from Prosper Marketplace Inc. It is beneficial to have a high prosper score in order to have a row Annual percentage return. According to the plots, borrowers with the lowest rating (HR) received the highest APR percentage, while borrowers with the highest rating (AA) received the lowest APR percentage.

## Author

👤 **Shyaka Kevin**
- LinkedIn: [Shyaka Kevin](https://www.linkedin.com/in/shyaka-kevin/)

## Acknowledgment 

-   [SynchVR](https://www.syncvr.tech/)