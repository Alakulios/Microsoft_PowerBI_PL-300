Completing this project involved creating measures using DAX to analyze year-over-year sales performance for Adventure Works.

First, I created a measure called Revenue using the SUMX function. This measure multiplies the Total Sales column by the Quantity column from the Sales table to calculate total revenue. I formatted this measure as currency with two decimal places for clarity.

Next, I created the RevenuePY measure to calculate the previous year’s revenue. This was done using the SAMEPERIODLASTYEAR function within CALCULATE to apply a time intelligence filter. The measure was also formatted as currency with two decimal places.

Finally, I created the Revenue YoY measure to calculate the year-over-year percentage change in revenue. Using the DIVIDE function, I divided the difference between Revenue and RevenuePY by RevenuePY. This measure was formatted as a percentage with two decimal places.

To visualize these results, I updated a matrix in Power BI by adding the Revenue, RevenuePY, and Revenue YoY measures to compare performance across months and years. These steps demonstrated my ability to use DAX and time intelligence functions to analyze business performance effectively
