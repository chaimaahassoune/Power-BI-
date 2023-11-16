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
 4. **Task 4 :**

#### 1. Importing Data

 - Import all five tables from the Excel File called “Section Six Data Extract” into Power Query Mode.

#### 2. Creating Username Column

 - Create a “Username” column inside dim_Customer table from the email address column. Extract text before the “@” symbol.          Label the column as “Username”.

#### 3. Handling Null Values

- Scan the dim_Customer table and remove columns with lots of Null values.

#### 4. Model Connections

- Import the tables into the model and check the connections between tables to ensure every table is connected.

 #### 5. Creating Measures Table

- Create #Measures table using DAX.

#### 6. Creating Date Table

- Create dim_Date table using “fact_InternetSales[ShipDate]” column and add columns like “Year”, “Month”, etc. Ensure             correct sorting for the Month column.

#### 7. Dynamic Currency Measure

- Create a dynamic measure for selected currency, returning sales amount in the selected currency or indicating "No             currency selected."

#### 8. Dynamic Title Measure

- Create a dynamic measure for the title to display “Sales Amount in [Selected Currency] vs All Currencies” or “Please             Select Currency from the Dropdown Menu.”

#### 9. Time Comparison Measures

- Create measures for Previous One Month, Previous Three Months, and Previous Six Months.

#### 10. Last Execution Time Measure

- Create a measure to display the time the report was last opened, with text “Executed: Date and Time.”

 #### 11. Header Styling

- Implement a header with a background color (optional) and line color #e8d400.

#### 12. Inserting Logo

- Insert a logo from 3.Images inside the header and resize accordingly.

#### 13. Creating Buttons

- Create buttons for “Clear Filters,” “Users,” “Currency,” and “Sales Territory” within the header. Apply specified outline colors.

#### 14. Executed Measure Display

- Place the Executed Measure inside the header on the right using a Card Visual, resized accordingly.

#### 15. Dropdown Menus

- Create dropdown menus using bookmarks for Users, Currency, and Sales Territory. Apply outlined color #e8d400.

#### 16. Bookmark for Clearing Filters

- Create a bookmark that clears all the filters and apply it to the “Clear Filters” button.

#### 17. Timeline Slicer

- Import Timeline Slicer into the visualizations panel. Position it below the header. Change the selected cells color to #e8d400.

#### 18. Sales Amount Boxes

- Create three boxes to show Sales Amount in Selected Currency, Sales Amount for All Currencies in Previous Month, and Sales Amount for All Time for All Currencies. Apply outlined color #e8d400.

#### 19. Increasing Canvas Size

- Find out how to Increase Canvas Size to 1720h x 1280w.

#### 20. Dynamic Title Positioning

- Position the Dynamic Title Measure in the middle inside a card visual with appropriate font size.

#### 21. Line and Stacked Column Chart

- Create a visual showing Sales Amount in All Currencies, split by month name. Customize colors and formatting as specified.

#### 22. Additional Dynamic Title Measure

- Create an additional dynamic title measure based on the Sales Territory Dropdown button from the Header.

#### 23. Map Visual for Products Sold

- Show the Number of Products Sold by Country inside a map visual. Customize colors as specified.

#### 24. SalesTerritory Table

- Create a table showing SalesTerritory along with Sales Amount as %, Total Sales Amount, and Sales for Previous One Month, Three Months, and Six Months. Apply conditional formatting to Total Sales Amount %.

#### 25. Testing and Bonus

- Test out the dashboard to ensure everything works in sync. Bonus: If possible, change the boxes inside the Currency dropdown to “Single Select” mode.


