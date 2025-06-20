# Data-Cleaning-and-Preprocessing

📁 File Name: marketing_campaign_1.csv
This file contains marketing campaign data with customer demographics, product purchases, and campaign responses.

✅ Data Cleaning Steps Performed in Excel
Checked and Handled Missing Values:

Applied filters and conditional formatting to identify blanks.

No missing values were found in the dataset.

Removed Duplicate Rows:

Used Data → Remove Duplicates to eliminate any repeated entries.

Standardized Text Values:

Used PROPER(), LOWER(), and Find & Replace to clean and unify values in columns like education and marital_status.

Converted Date Formats:

Converted dt_customer from text to date using Text to Columns and applied dd-mm-yyyy format.

Cleaned Column Headers:

Renamed columns to follow consistent formatting (lowercase, no spaces, underscores).

Checked and Fixed Data Types:

Ensured numeric columns were correctly formatted as numbers and dates as date format.

Verified with functions like ISTEXT(), ISNUMBER(), and ISDATE().

⚠️ Additional Observations:
year_birth column had only one value: 1905, which may indicate placeholder or incorrect data.

Columns like z_costcontact and z_revenue had constant values and can be dropped if not useful for analysis.

📌 Outcome:
The dataset is now clean, standardized, and ready for analysis or dashboarding in Power BI or Python.

