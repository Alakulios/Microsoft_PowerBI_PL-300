
Completing this task involved several steps. First, I modified the Total Revenue measure to calculate Non-US Sales. Using the CALCULATE function, I applied a filter to exclude sales from the United States by specifying that the Country column in the Region table must not equal "United States." After creating the measure, I formatted it as currency with two decimal places for better readability.

Next, I created a measure for Black Road Bikes Sales. This measure used the CALCULATE function with filters for the Subcategory column to include only "Road Bikes" and the Color column to include only "Black." Like the previous measure, I formatted it as currency with two decimal places for consistency.

Finally, I created a measure for Sales by Sales Managers. Here, I used the CALCULATE function to filter the Title column in the Salesperson table, applying the CONTAINSSTRING function to include only rows containing the word "Manager." I saved the project with a new name to preserve these changes. These steps demonstrate the flexibility of the CALCULATE function in creating targeted, business-specific measures.
