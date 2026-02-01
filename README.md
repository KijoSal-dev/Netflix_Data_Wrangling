# Netflix_Data_Wrangling
## Overview

This project demonstrates practical data wrangling skills using Python and Pandas on a real-world dataset sourced from Kaggle. The dataset contains information on Netflix movies and TV shows, including titles, release years, cast, directors, ratings, duration, and availability details. The goal was to transform raw, messy data into a clean, structured, and analysis-ready dataset.

## Why I Did This Project

The primary purpose of this project was to strengthen my hands-on skills in data discovery, cleaning, transformation, and validation—core competencies in data analytics and artificial intelligence. Real-world datasets often contain missing values, inconsistencies, and formatting issues, and this project provided an opportunity to practice systematic data wrangling techniques in a realistic scenario. It also forms part of my academic training under the Cyber Shujaa Data Analytics program and contributes to my professional data portfolio.

## What I Did

The project followed a structured data wrangling workflow:

1. Data Loading and Discovery
Loaded the Netflix dataset from a CSV file into a Pandas DataFrame.
Explored the dataset structure, data types, missing values, and duplicate records.

2. Data Structuring
Converted date fields into proper datetime formats.
Extracted numeric and categorical components from complex fields such as duration.

3. Data Cleaning
Removed duplicate records and unnecessary columns.
Handled missing values using logical imputation strategies, including director–cast and director–country relationships.
Clearly labeled unresolved missing values as “Not Given”.
Removed records with critical missing information.

4. Validation and Quality Checks
Applied logical consistency checks (e.g., validating release year against date added).
Verified data types, completeness, and overall dataset integrity.
Sampled records for visual inspection and reset the dataset index.

5. Publishing
Exported the final cleaned dataset as a CSV file.
Published the complete notebook with public access for reproducibility.

## Outcome

The final output of this project is a cleaned and well-structured Netflix dataset that is ready for analysis or visualization. The project reinforced best practices in data wrangling, including careful data inspection, thoughtful handling of missing values, and validation using business logic. Additionally, the completed notebook and dataset serve as a portfolio artifact that demonstrates my ability to work with real-world data using Python.

## Tools and Technologies Used

Python
Pandas
NumPy
Kaggle Notebooks

## Dataset Source

Netflix Movies and TV Shows Dataset – Kaggle

## Author

Salome Kungu
Cyber Shujaa Program – Data Analytics
