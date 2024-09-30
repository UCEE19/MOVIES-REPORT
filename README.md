# MOVIES-REPORT
## Table of contents 

- Project Review
- Data Source
- Tools Used
- Data preparation and Data Cleaning
- Data Analysis
- Visualization in Power BI
- Findings
- Limitations

## Project Overview

This project explores a dataset containing various attributes of movies, such as titles, writers, directors, stars, budget, rating , runtime and additional details. The goal is to derive insights into trends and patterns within the movie industry.

 ## Data Source

The dataset is sourced from the “MOVIES.csv”file. It includes a comprehensive collection of movie details up to 2020.

## Tools Used

- Excel: For initial data cleaning and organization.

- SQL Server Management Studio (SSMS): For querying and performing complex data manipulations.

- Power BI: For data visualization and interactive reporting.

## Data Preparation and Data Cleaning Process in SSMS Workbench

- Database Creation: Establish a database named "MOVIES Report Project”.
- Import Data: Import the MOVIE dataset from the "MOVIES.csv" file into the database.
- Check Data Types: Review data types of all columns.
- Standardize Date Formats: Use SQL functions to standardize date formats and convert text to date data types.
- Handle Special Characters: Rename columns with special characters using the "ALTER TABLE" command.
- Address Missing Values: Identify and handle missing values, particularly in date columns like "termdate."
- Update Data Types: Modify data types as needed, such as changing text to date or integer.
- Ensure Data Integrity: Validate data integrity and consistency throughout the process.

## Questions Answered in Data Analysis process in SSMS workbench

- List all movies in the dataset
- Show all details for a movie with a specific name
- List all unique genres
- Top 10 highest grossing movies
- Top 5 movies by rating
- Total votes for all movies
- Average rating of movies by genre
- Find movies released after 2010
- Find movies with budget greater than 100000
- List movies by a specific director
- Find all movies of a specific genre
- Find movies with runtime greater than 2 hours
- Find the company associated with the highest grossing movie
- Calculate Profit(gross-budget) for each movie
- List movies with the highest profit margin
- Find the average runtime of movies by Country
- Find movies where the director and writer are the same person

## Visualization in Power Bi

- Created visualizations including ;
- Bar Charts showing Budget per movie
- Line Charts depicting trends in movie released by genre
- Pie Charts showing Budget per Country

## Findings

Movies with higher budgets tend to perform better at the box office.
Certain genres, such as action and drama, show consistent popularity over the years.
Collaboration between successful writers and directors significantly enhances movie ratings.

## Limitations 

The dataset may not be comprehensive or up-to-date, potentially affecting the accuracy of insights.
Data biases, such as underrepresentation of certain genres or demographics, could skew results.
The analysis may not account for external factors influencing box office performance, such as marketing efforts or competition.
  
