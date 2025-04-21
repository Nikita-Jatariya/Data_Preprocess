# Data_Preprocess

Step 1: Understanding the Data

-Review the columns and understanding the data (e.g., Title, Type, Director, Cast, Country, Release_Year, Rating, Duration, etc.).
-Identifying missing values, inconsistencies, duplicates, and formatting issues.

Step 2: Handling Missing Values

-Check for blanks: Using Excel's Filter to highlight empty cells.
-Fill missing values: Used "Unknown" for text columns (e.g., Director, Cast), Used "Not Specified" for Country or Rating.

Step 3: Standardize Data Formats

-Dates/Years: Ensuring dates are in a consistent format (e.g., YYYY).
-Rating: Standardize labels (e.g., "TV-14", "TV14" → "TV-14").

Step 4: Clean Text Columns

-Titles: Remove extra spaces or special characters using TRIM() and SUBSTITUTE().
-Country: Standardize country names (e.g., "USA" vs. "United States").

Step 5: Remove Duplicates
-Used Remove Duplicates to eliminate duplicate entries.

Step 7: Validate Numerical Data
-Release Year: Ensure years are realistic (e.g., no future years like 2030).
-Duration: Check for outliers (e.g., a movie with 5000 minutes).

Step 8: Export Cleaned Data
-Save the cleaned file as a new Excel workbook (e.g., Netflix_Cleaned.xlsx).



