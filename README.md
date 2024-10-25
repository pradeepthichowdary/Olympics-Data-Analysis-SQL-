# Olympic Games Data Analysis

## Introduction
This repository contains SQL queries designed to analyze a unified dataset of Olympic Games data, combining both winter and summer games. The dataset encompasses various attributes, including athlete demographics, event participation, and medal records, allowing for a comprehensive examination of trends, distributions, and insights within the Olympic Games.

## Objective
The primary objective of this analysis is to uncover insights regarding athletes, events, and historical trends in the Olympics through structured queries. By analyzing the data, we aim to understand patterns such as:

- The impact of age and gender on athlete participation.
- Trends in the number of athletes over time.
- The distribution of new sports introduced in various Olympic years.
- Insights into host cities and the frequency of hosting.

## Problem Statement
The analysis addresses several key questions regarding Olympic participation and trends, including:

- What are the missing values in the dataset, and how do they affect the analysis?
- How does athlete participation change over the years by age and gender?
- What is the distribution of Olympic athletes by sex and how has it evolved?
- How many times has each city hosted the Olympics, and which cities have hosted both Winter and Summer Olympics?
- What new sports have been introduced, and how has the number of sports evolved over time?

## Results
The SQL queries provide insights into the following areas:

1. **Missing Values**: Identified columns with missing values and their counts.
2. **Age Analysis**: Calculated the percentage of records with age data, grouped by year, sex, and season.
3. **Athlete Participation**: Counted the number of athletes competing in each Olympic year and how many Olympics each athlete has participated in.
4. **Olympic Trends**: Analyzed the number of new teams and sports introduced in each Olympic year.
5. **Host City Insights**: Identified host cities and their frequency of hosting, along with determining cities that have hosted both Winter and Summer Olympics.

## Queries Overview
The SQL queries are categorized to facilitate various analyses:
- **Missing Value Analysis**: Queries to assess the completeness of data.
- **Age and Gender Analysis**: Queries to evaluate participation trends based on demographics.
- **Participation Statistics**: Queries to summarize athlete counts and event details.
- **Host City Analysis**: Queries to explore hosting patterns and insights.

## Usage
To execute the queries, ensure you have a compatible SQL database with the `winter_data` and `summer_data` tables containing the required fields. The dataset can be viewed as a unified view named `games_data`. 

Clone this repository and run the SQL scripts in your preferred SQL environment to explore the Olympic Games data analysis.

## Conclusion
This repository serves as a comprehensive resource for analyzing Olympic Games data, providing valuable insights into athlete participation and event trends. The structured SQL queries can be adapted and extended for further research and exploration in the domain of sports analytics.
