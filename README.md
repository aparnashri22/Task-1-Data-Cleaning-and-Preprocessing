# Task-1-Data-Cleaning-and-Preprocessing
📁 Dataset

Source: Kaggle - Customer Personality Analysis

File used: marketing_campaign.csv

🎯 Task Objective

To clean and preprocess the raw dataset using Microsoft Excel by handling missing values, removing duplicates, standardizing text formats, fixing date and column formats, and ensuring correct data types.

🧹 Data Cleaning Steps

✅ 1. Removed Duplicates

Used Excel's Remove Duplicates feature on all columns

Result: 10 duplicate rows removed

✅ 2. Handled Missing Values

Found missing values in the Income column using Filter → Blanks

Replaced missing Income values with the average income (e.g., 45,000)

✅ 3. Standardized Text Values

Cleaned Marital_Status, Education, etc. using:

=PROPER(TRIM(A2)) to fix inconsistent capitalization and spaces

✅ 4. Reformatted Date Column

Column: Dt_Customer

Applied format DD-MM-YYYY using Format Cells → Date

Ensured all values are in correct date format

✅ 5. Renamed Columns

Changed all column names to:

Lowercase

snake_case (e.g., Year_Birth → year_birth)

Removed any spaces/special characters

✅ 6. Checked Data Types

Ensured numeric columns like Income, MntWines, Kidhome are formatted as Number

Ensured Dt_Customer is formatted as Date

💾 Final Output

File: customer_personality_cleaned.xlsx

A clean, analysis-ready Excel sheet

📌 Tools Used

Microsoft Excel

📄 Summary of Changes

1. Removed 10 duplicate rows
2. Replaced 5 missing Income values with 0
3. Standardized categorical values using TRIM and PROPER
4. Converted Dt_Customer to consistent DD-MM-YYYY format
5. Renamed Dt_Customer columns to Joining Dates
6. Checked numeric and date data types
