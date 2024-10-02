Dataset Overview

The dataset, named messy_Data.csv, contains various fields that require cleaning to prepare it for analysis. This summary outlines the steps taken to address data quality issues, ensuring the data is consistent, accurate, and ready for further analysis.

1. Load the Data
   
The dataset was successfully loaded into a Jupyter notebook for inspection and processing.

3. Inspect the Data
   
Initial inspection revealed multiple inconsistencies across various fields, including missing values, duplicate records, irregular email formats, inconsistent naming conventions, and typos in department names.

5. Record QA Issues
   
Field-wise documentation of data quality issues includes:

-Email Field: Invalid formats and non-professional email addresses.

-Name Field: Presence of extraneous characters and inconsistent formatting.

-Join Date: Various date formats present.

-Department: Typos and inconsistencies.

-Salary: Presence of noise and outliers.

4. Handle Missing Values
   
-Missing values were identified in several fields. The approach taken:

-Filled missing numerical values with the median to reduce the impact of outliers.

-Removed rows where more than 50% of the data was missing.

5. Remove Duplicates
   
Duplicate records were identified and removed, ensuring each entry in the dataset is unique.

7. Correct Email Formats
   
The email field was thoroughly reviewed to:

-Correct invalid formats.

-Filter out only professional email addresses (e.g., those from company domains).

-Standardize all emails to the format username@domain.com.

7. Clean Name Fields
   
Name entries were cleaned by:

-Removing extraneous characters and words.

-Ensuring consistent formatting (e.g., capitalization of first letters).

8. Standardise Date Formats
   
All entries in the 'Join Date' column were converted to a consistent format (YYYY-MM-DD), facilitating easier chronological analysis.

10. Correct Department Names
    
The 'Department' column was standardized by:

-Identifying and correcting typographical errors.

-Ensuring all entries are consistent, such as HR, Engineering, Marketing, Sales, and Support.

10. Handle Salary Noise
    
Salary values were reviewed for noise and outliers bu were found clean

Conclusion

The data cleaning process has improved the quality and consistency of the dataset, making it suitable for further analysis. The steps outlined above addressed key issues in the dataset, ensuring that the final output is reliable and structured for effective use in subsequent analytical tasks.
