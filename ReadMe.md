# Excel Data Cleaning Project 

Data cleaning project using Excel. Includes raw data, cleaned dataset, and documentation of the cleaning steps.
The goal was to transform a messy dataset into a clean, analysis-ready table suitable for reporting and dashboard creation.

## 1. Formatting & Structure
Autofit row height and column width  
Standardised all headers (centre aligned, clean text)  
Converted dataset into a clear table layout

## 2. Cleaning Client & Contact Names
Used Find & Replace ( * ) to remove parentheses in the Client column  
Added a new temporary column  
=LOWER() to make names consistent  
Copied & pasted values  
Applied =TRIM() to remove extra spaces  
Applied =PROPER() to correct capitalisation  
Replaced original names with cleaned versions  
Deleted helper column.

## 3. Splitting Department & Region
Created a new column called Region  
Used Text to Columns to split “Department, Region” into two clean separate fields.  

## 4. Handling Missing & Duplicate Data
Removed all duplicate rows using Excel’s built-in duplicate removal  
Used Find and Select, Special, to locate all Blanks  
Filled all empty cells with "N/A" using Ctrl + Enter.

## 5. Fixing Profit Margin Errors
Used an IFERROR formula in the Profit Margin column to handle invalid values:  
=IFERROR(Profit/Revenue, "N/A")

## 6. Final Presentation Improvements
Removed gridlines for cleaner presentation  
Added background colour to headers  
Used bold fonts to make sections clearer.   

Produced a clean final dataset ready for analysis.

## Skills Used
Data cleaning  
Excel formulas (TRIM, PROPER, LOWER, IFERROR)  
Text to Columns  
Handling missing data  
Data formatting  
Table structuring  
Business-ready dataset creation.
