# Power BI Certification Project

This repository contains the Power BI projects completed as part of the 365 DATA SCIENCE certification. The projects involve creating visualizations, data modeling, and implementing measures based on the provided dataset.
## Tasks 
1. **Task 1 :**
   - Import all tables from the provided dataset.
   - Create a `dim_Date` table using the `ShipDate` from `fact_InternetSales` with the following columns:
      1. Year
      2. Month
      3. MonthName
      4. DayOfWeek
      5. Quarter
      6. YearQuarter
   - Connect the `dim_Date` table with `fact_InternetSales` on `ShipDate`.
   - Visualizations using Ask a Question:
     - Sales Amount by Currency, sorted by currency name.
     - Sales Amount by Month, sorted by the correct Month Order.
     - Matrix Table showing Sales Amount by Email Address per Currency.
     - Bonus Points: Increase font size of visuals on Titles, Values, and Axis. Change the Style of the Matrix table.

  2. **Task 2 :**
     -  Create a Measures table that lives on top of all tables
     -  Create measures that Find the Total Sales for US as Number and also as Percentage
     -  Create a button to switch between Number and Percentage, when we click on Number, we should see the Number Measure, when we click Percentage, we should see Percentage Measure
     -  Create a bar chart that shows the Sales Amount for each country
     -  Change the order of Country, countries need to be ordered in alphabetical order
     -  Dynamic text box to adapt to changes based on user selection, the box needs to say which country is selected and if no country is selected we should see something along the lines “No Country Selected”
