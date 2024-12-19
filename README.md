# PySpark-Data-Cleaning

Initial Dataset Overview:
Shape: (195 rows, 35 columns)

Data Cleaning and Preprocessing Steps:

1. Dropped Unnecessary Columns: Removed irrelevant columns that did not contribute to the analysis.
2. Renamed Columns: Standardized column names for better readability and consistency.
3. Removed Unnecessary Text: Cleaned up text data by removing unwanted characters such as emojis, %, $, spaces, etc.
4.  Typecasting: Converted relevant columns to numeric types for accurate analysis and modeling.
5. Categorical Encoding: Transformed categorical columns into numeric values using “StringIndexer”
6. Handling Missing Data:
   - Imputer: Applied to fill missing values in numerical columns.
   - Null Values: Dropped rows with null values after imputation.
7. Duplicate Handling: Removed duplicate rows to ensure data consistency.
8. Final Cleanup: Dropped any remaining rows with null values to maintain data integrity.

Final Dataset Overview:
Shape : (188 rows, 37 columns)
