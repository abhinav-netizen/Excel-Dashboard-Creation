# Excel-Dashboard-Creation
A dashboard of coffee sales though out the years created with pivot tables 

Project Overview
-The goal was to transform raw sales data into an interactive dashboard, allowing users to filter and analyze coffee sales by product, date, and region with ease.

Preperation
-In the orders sheet most the data were missing and often in other sheets within the same xlsx file
-colums from the other sheet was imported into the orders sheet using the XLOOKUP() function 
-the end cols(coffe details) were added using the INDEX() function since it needed most of the cols
-The orders sheet was then transformed into a table making pivot sheets easy to use
-Duplicates were also check and none were found using the "check duplicates" function in excel

Dashboard Creation
-Pivot tables were created in a seperate sheet with sclicers and linked with each other 
-There are three visualisation using pivot tables and all were duplicated from one another to intergrate all the sclicers
-Finaly it was copied into the new sheet called dashboard and scicrers were connected with all the sheets
-The size were adjusted and colours were added to improve the look of the dashboard

Features
-Interactive filtering with Slicers and Timeline
-Year-over-year coffee sales visualization
-Total sales by country visualisation
-Top 5 customers visualisation
-Clean, user-friendly design
-Built entirely in Excel without macros
