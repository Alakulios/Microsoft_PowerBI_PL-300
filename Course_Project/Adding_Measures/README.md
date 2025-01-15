Adventure Works needs your help calculating its sales data using quick measures and DAX. Its main objective is to compute the running total for sales of its product line. This accumulated data will help the company analyze its sales trend based on various factors, like time, categories, salespersons, and resellers. It can then use these insights to make informed decisions.

Step 1: Download the Adventure Works Power BI project.
Download and save the Power BI project file Adventure Works.pbix. The file comprises a data model containing five data tables: Salesperson, Region, Date, Products and Sales.

Data model
Step 2: Create a Quick Measure.
Once the data is loaded into the data model, create a new quick measure called Running Total in Year to calculate the running total of Adventure Work’s sales. You must create this measure using the Total Sales column from the Sales table and the Year column from the Date table.

Format the measure as currency data type within two decimal places.

Tip: You can create this measure by using Power BI’s Quick Measure feature.

Step 3: Create a measure using a DAX query.
Create an additional measure in the Sales table called Total Revenue using a DAX query. The measure must calculateAdventure Work’s total revenue by multiplying the Quantity of each product by its respective Unit Price.

Format the measure as currency data type within two decimal places.

Tip: You can create this measure using the SUMX DAX function in the formula bar of Power BI’s desktop interface.

Step 4: Save the Power BI project.
Save your Power BI project to your local computer.

Tip: Make sure you select an appropriate project name and folder path.
