# Excel Data Cleaning Project
## Project Overview
This project demonstrates the process of cleaning and transforming a retail product dataset using Microsoft Excel. The objective was to improve data quality and consistency by handling missing values, correcting inconsistent data, checking for duplicate records, restructuring columns, formatting data, and applying conditional formatting.
## Dataset
The dataset contains product-related information, including:

- Product ID
- Product Name
- Brand Name
- Price
- Quantity
- Category

The Excel workbook contains two sheets:
- **Dataset** – Original dataset before cleaning
- **Cleaned_Data** – Dataset after the cleaning and transformation process

## Data Cleaning and Transformation

### 1. Handling Missing Values
- Checked the **Price** column for missing values.
- Compared the mean and median to determine an appropriate method for handling missing prices.
- The median value of **$130** was selected because the mean of **$309.35** was influenced by higher-priced products.
- Missing values in the **Category** column were identified and handled by comparing products with similar product names. Where a suitable category could not be determined, **Unknown** was used.

### 2. Correcting Inconsistent Data
- Identified inconsistent text formatting in the **Product Name** column.
- Corrected spelling errors and inconsistent values in the **Category** column.
- Standardized product names and category values using Excel's Find and Replace functionality.

### 3. Checking for Duplicates
- Checked the dataset for duplicate records based on the entire row.

### 4. Splitting and Merging Data
- Split the **Product ID** into separate **Manufacturing Date** and **Country Code** fields.
- Combined **Product Name** and **Brand Name** to create a new **Product Brand** field.

### 5. Number and Date Formatting
- Formatted the **Price** column using currency formatting.
- Standardized the **Manufacturing Date** values into a consistent date format.

### 6. Conditional Formatting
- Applied data bars to the cleaned **Price** values to make differences in product prices easier to identify visually.
- Applied a custom conditional formatting rule to highlight products belonging to the **Electronics** category.

## Tools Used
- Microsoft Excel

## Project File

The repository contains the completed Excel workbook:

`Excel-Data-Cleaning-Project.xlsx`
