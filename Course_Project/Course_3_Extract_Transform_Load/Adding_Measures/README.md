Completing this task involved two distinct steps.<br/>

First, I created a quick measure called Running Total in Year using the Quick Measure tool on the Home tab. For this measure, I selected the Total Sales column from the Sales table and the Year column from the Date table as arguments. After generating the quick measure, I formatted it as currency and set it to display with two decimal places for better readability. <br/>

Second, I created a custom measure using a DAX query to calculate Adventure Work's Total Revenue. This measure multiplies the Quantity of each product by its respective Unit Price and sums the results across all rows in the Sales table. The measure dynamically adjusts based on filters, ensuring accurate revenue calculations for specific time periods or product categories.
