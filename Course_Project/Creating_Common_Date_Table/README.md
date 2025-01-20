
Completing this project involved creating a common date dimension table in Power BI to enable time intelligence analysis for Adventure Works.

First, I created a Date table using the CALENDAR function in DAX. I specified a date range from January 1, 2017, to December 31, 2021, to encompass the entire sales dataset. After generating the table, I formatted the Date column as a Date data type for consistency and renamed it accordingly.

Next, I expanded the table by adding related columns such as Year, Month, Month Number, Day of the Week, and Week Number using various DAX functions like YEAR, FORMAT, MONTH, WEEKNUM, and WEEKDAY. These columns provide additional granularity for time-based analysis.

Once the table was complete, I marked it as a Date Table to ensure Power BI recognized it for time intelligence purposes. Finally, I established relationships between the new Date table and the existing fact table in the data model to integrate it fully.

These steps demonstrated my ability to create and configure a common date table, enabling efficient time-based analysis and reporting in Power BI.
