# Datahut QA Assignment

## Problem Statement:

The provided dataset contains inconsistencies, errors, missing values, and duplicates, making it unsuitable for analysis in its current state.

My task is to systematically clean and preprocess this dataset to ensure its accuracy, completeness, and reliability.

## Objective:

The aim of this assignment is to systematically clean and preprocess the given messy dataset to ensure its suitability for further analysis.

This involves identifying and rectifying inconsistencies, handling missing values, removing duplicates, correcting errors, and standardizing data formats.

By the end of this task, the dataset will be transformed into a clean, reliable, and structured format, ready for accurate and meaningful analysis.

## INSPECT THE DATA:
### Methodology: 
The dataset was examined to understand its structure, data types, and potential inconsistencies. Initial inspection was done using methods such as .head(), .info(), and .describe(). These methods provided insight into the first few rows, column data types, summary statistics, and the presence of missing values.

### Findings:
     -The dataset contained 11,000 rows and 8 columns.
     -There are Null values in all columns except Id.
     -Existence of duplicate Id’s.
     -Inconsistencies in Name and Department Columns.
     -Incorrect email formats in Email column and Invalid date formats in Join Date column.
     -Noise in Salary column.

## RECORD QA ISSUES:
    -ID: Duplicate entries for ID, with slight variations in Name, Department (e.g., "HR" vs. "HRs"), and Join Date. In some cases, one row had the correct email while another had the 
     correct salary, leading to inconsistencies across fields.
    -Name: The Name column contained extraneous words and inconsistencies, requiring cleaning to ensure uniform formatting.
    -Email: Unformatted and non-professional emails.
    -JoinDate: Inconsistent date formats.
    -Department: Inconsistent and non-standardized department names.
    -Salary:Noise in the Salary column.
    -Age: Null values in Age column.

## OUTCOME 
After the data cleaning process, the dataset was reduced to 6,838 rows and 7 columns. All duplicate records were successfully merged, ensuring the most accurate and up-to-date information for each entry, including valid email addresses, standardized names, and departments. The cleaned dataset is now ready for further analysis.



