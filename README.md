<h1>Project Overview </h1>
<p>
  This end-to-end data analysis project focuses on understanding customer demographic factors that drive bike purchasing decisions. 
  The objective was to transform raw sales data into a functional, interactive dashboard that provides clear, actionable insights for market analysis and retail strategy.
</p>

<h2>Repository Structure</h2>
<p>
  This repository is organized to showcase the entire data workflow, from raw input to final visualization:

 Dataset/

raw_data.csv: The original, untouched customer data.

cleaned_data.csv: The dataset after all cleaning and transformation steps were applied.

 Image/

dashboard.png: A high-resolution screenshot of the final Excel Dashboard for quick viewing.

 Project File/

Bike-Sales-Analysis-Workbook.xlsx: The master Excel file containing four distinct, labeled sheets: Raw Data, Working Sheet (Cleaned Data), Pivot Tables, and Dashboard.
</p>

<h2>Data Cleaning Process</h2>
<p>
The raw data underwent several transformation steps to ensure accuracy and readability:

Standardizing Values: Updated "M" and "S" in the Marital Status column to "Married" and "Single." Standardized Gender from "M/F" to "Male" and "Female."

Data Formatting: Adjusted the Income column to currency format.

Custom Columns: Created an Age-Bracket column using nested IF statements to categorize customers into:

Adolescent (Under 31)

Middle Age (31–54)

Old (55+)

Duplicates: Removed redundant entries to ensure each customer ID is unique.
</p>

<h2>Analysis & Insights</h2>
<p>
Using Pivot Tables, I explored several key metrics:

Income vs. Purchase: Analysis shows that customers who purchased bikes generally have a higher average income (approx. $58,000) compared to those who did not (approx. $55,000).

Commute Distance: Customers with a commute of 0-1 miles are the most likely to purchase a bike.

Age Demographics: The Middle Age group represents the largest segment of bike buyers, followed by the Old and Adolescent categories
</p>
