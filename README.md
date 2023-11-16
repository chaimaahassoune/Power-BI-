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
 3. **Task 3 :**
      ##### Your task is to create a dashboard that looks aesthetically pleasing. Files can be located in Section Five Data Extracts, please import all columns from the excel file.The dashboard should contain:
        -  Header, background color to be #101D42
        -  Slicer with Colors from dim_Product, to be placed inside the Header
        -  Measures table (using DAX) with measures for Products Sold, Total Customers, Total Sales Amount
        -  Three boxes to show Total Sales Amount, Products Sold and Amount of Customers.
        -  Each box should have the same background color as the Header, and also contain an image.
        -  The values need to be shown inside the card visual. Boxes, images and values need to be aligned accordingly, values’ font size should be increased.
        -  Two boxes with the same background color as Header.
        -  The first box should contain a donut chart showing the split between Male and Female, switch off the title from the donut chart and use Text Box.
        -  The text inside Text Box should say “Total Products Sold Male/Female Split”, font size to be bold, 24px, color to be #DB162F . Donut labels should be increased to 14 px.
        -  The donut colors should be white 20% Darker for Male and for Female use #DB162F.
        -  The second box should have a title called “Total Products Sold by Country”, same font size and color settings as the first box.
        -  Total products sold by country should be displayed using a bar chart. Title should be switched off from the bar chart, font size should be increased on both y and x axis.
    
