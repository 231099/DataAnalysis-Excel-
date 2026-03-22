<h1>Project Overview </h1>
<p>
  This project analyzes customer demographic data to identify patterns and trends that influence bike purchasing decisions. 
  The goal was to process raw sales data into a functional dashboard that provides actionable insights for a retail strategy.
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
