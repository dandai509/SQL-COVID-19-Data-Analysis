# SQL-COVID-19-Data Analysis

## Project Goal

This project explores and analyzes global COVID-19 data using SQL to uncover trends, assess impacts, and evaluate vaccination progress across countries and continents. The analysis focuses on real-world data related to infection rates, death rates, and vaccination rollouts, with a deep dive into New Zealand.

The project demonstrates skills in:

- SQL data querying and aggregation

- CTEs, temp tables, views for modular analysis

- Joining datasets

- Building metrics and KPIs (e.g., Infection Rate, Death Percentage)

- Data transformation for BI tools (e.g., Power BI)

## Datasets Used

CovidDeaths: Contains daily reported cases, deaths, and population data.

CovidVaccinations: Contains data on vaccine distribution by country and date.

Both datasets were imported and verified from the Our World in Data public source and stored in SQL Server under the SQLPROJECT.dbo schema.


## Exploratory Data Analysis

- Check two tables to see if Data has imported correctly 

![1](https://github.com/user-attachments/assets/ae2aee08-6952-4a13-b819-efa68baa9440)
![3](https://github.com/user-attachments/assets/867dba6e-bac0-448e-8915-ff4c875658b1)


- Check overall new cases per day since Feb 2020 for each coutry 

![4](https://github.com/user-attachments/assets/5eb5ba78-4758-40df-a2fe-7a25b67cdf6e)
![5](https://github.com/user-attachments/assets/c04de501-15c7-4ea1-99c5-535251c85b3f)


- Check Total Cases vs Total Deaths in NZ, The table shows the chance of dying if people contract COVID-19 in NZ

![6](https://github.com/user-attachments/assets/e93de98c-e4e0-4525-966d-93cd448fb539)

![7](https://github.com/user-attachments/assets/6bbc35ea-6eb5-4580-b166-e052b3d6d07e)

- Check Total cases vs Population in NZ, the table shows COVID infection rate in NZ from Feb 2020- April 2021

![22](https://github.com/user-attachments/assets/feebbeff-0315-4872-8573-4565aab0b62d)
![23](https://github.com/user-attachments/assets/27dd2811-0e97-44f9-acef-fdc318b79cec)

- Check the Highest Infection rate as per coutry, NZ Ranked 179, one of the lowest infection rate among developed countries 

![8](https://github.com/user-attachments/assets/5a6d056e-6b3e-47b4-8964-e8b22f669b8a)
![9](https://github.com/user-attachments/assets/fb7e9617-3717-406d-bce7-e282ee517a18)

- Check The Highest Death Count per population as Continent, Europe has the highest

![10](https://github.com/user-attachments/assets/2318e5ff-41ce-4db3-be02-697ca16bd115)
![11](https://github.com/user-attachments/assets/854dcfa3-5c43-4ae7-a9f6-c10d81577162)

- Check Overall World COVID cases and death by dates 

![12](https://github.com/user-attachments/assets/cb1ab214-1df8-4f08-84e3-b9cc45e7d7a7)
![13](https://github.com/user-attachments/assets/5a8eed4a-58c4-4b21-a03c-21fbfc68df2a)

- Join COVID death table and Covid Vaccination table together 

![14](https://github.com/user-attachments/assets/55cb630a-10a4-4de6-82f3-b472f1da0fde)
![15](https://github.com/user-attachments/assets/a13a04c4-2d30-4c49-ada0-048412a66f2f)

- Check World Total Population vs Vaccination

![16](https://github.com/user-attachments/assets/ee235176-38c1-4004-bbd4-9930a7de9f26)
![17](https://github.com/user-attachments/assets/51d926a3-fcb6-46e4-94c2-5b50a33bd112)

- Find out rolling total vaccinated population

![18](https://github.com/user-attachments/assets/376297ad-38db-4962-8dcb-8348c2450ba4)
![19](https://github.com/user-attachments/assets/22f8d119-900a-40de-a4f5-d8e57379bf76)

- Using CTE to perform calculation on partition by previous query

![20](https://github.com/user-attachments/assets/644ce81b-159c-4532-a112-9495723a2f59)
![21](https://github.com/user-attachments/assets/b25cb2d8-9353-43c6-abfa-5fe77e77af00)


- Using TEMP TABLE to perform calculation on Partition By in previous query

![24](https://github.com/user-attachments/assets/d67d434f-96d7-4bd8-9e72-4f19a7a14929)

![25](https://github.com/user-attachments/assets/3c7ccc87-5c5a-45d9-b140-9df001f9d868)
