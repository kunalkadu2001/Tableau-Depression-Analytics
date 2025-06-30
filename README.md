# Tableau-Depression-Analytics
This project analyzes student depression data using Tableau. Data was cleaned in MS SQL Server by handling nulls, modifying gender values, and creating age groups, then visualized to show patterns in sleep, study habits, and stress factors.

## Project Objective:
- To visualize and analyze factors affecting student depression, such as sleep, study habits, academic pressure, and financial stress, using cleaned data in Tableau.

## Dataset Used
- <a href="https://github.com/kunalkadu2001/Tableau-Depression-Analytics/blob/main/Depression%2BStudent%2BDataset.csv">Dataset</a>

## Questions

- What percentage of students report high academic pressure?
- How many students sleep less than 6 hours per day?
- What is the average study satisfaction level across age groups?
- How many students are affected by financial stress?
- Which gender reports higher levels of depression symptoms?


## Process

- Imported the raw student depression dataset into MS SQL Server.
- Cleaned the data by removing null values and standardizing gender entries (Male To M, Female To F).
- Created a new Age Group column (A1, A2, A3) based on age ranges.
- Connected the cleaned data from SQL Server to Tableau Desktop.
- Built interactive visualizations to explore factors like sleep, study hours, academic pressure, and financial stress.

## Dashboard
- ![Screenshot 2025-06-30 182915](https://github.com/user-attachments/assets/69b3e8a0-56e3-4ff3-8ac2-98efdca5eda6)


## Insights

- High academic pressure: 47% of students
- Students sleeping < 6 hours: 28 students
- Average study satisfaction (by age group):
    A1: 2.9
    A2: 3.4
    A3: 3.7
- Students with financial stress: 52 students
- Gender with higher depression symptoms: Female (F)











