# E-commerce-Sales-Analysis--Data-Cleaning
End-to-end data cleaning and sales performance analysis of an e-commerce dataset.

Project Overview

Data Transformation & Cleaning Steps

Data Deduplication: Removed duplicate records to ensure sales and revenue figures are accurate and not double-counted.

Text Standardization: Used functions like TRIM to remove extra spaces and PROPER to ensure consistent naming (e.g., converting "shoe" to "Shoes").

Handling Missing Values:

Imputation: Filled blank cells with logical values based on existing data.

Row Deletion: Removed unnecessary rows that did not impact the overall analysis.

Data Type Conversion:

Converted text-based numbers into actual numeric values using Find & Replace (Ctrl + H).

Standardized date formats to enable time-series analysis (Daily Sales Trends).

Feature Engineering (Calculations):

Calculated missing Total values using the formula: Price * Quantity.

Used business logic to fill in missing unit prices.

Data Normalization: Set consistent currency formats and cleaned up decimal points to make the report easy to read.

Exploratory Data Analysis (EDA): Created charts and visuals to identify key business problems, such as high return rates and profit/loss drivers.
