# AdventureWorks-Tableau-Dashboard

AdventureWorks Data Visualisation Project using Tableau

PLEASE NOTE: I used Tableau Public to build the dashboard. Due to Tableau Public's limitations, the worksheets used to create the visuals are visible.

The three dashboards can be found on the first three pages.
For details, please view the Word document "Adventure Works Dashboard Documentation" attached.

The AdventureWorks sample database

1.	About the dataset

AdventureWorks is a free public retail sales dataset offered by Microsoft. The dataset can be  retrieved here: https://github.com/microsoft/powerbi-desktop-samples/blob/main/AdventureWorks%20Sales%20Sample/AdventureWorks%20Sales.xlsx

2. Dashboard objectives 

Potential Stakeholders could include Sales or Product teams. Therefore, the objectives of the dashboard are to identify top customers, understand product (category) trends and track KPIs across regions. Specifically, the interactive dashboard reflects the main KPIs monthly, ranging from the year 2017 to 2020. To understand the differences between customers' product interests, interactive reports were built to analyse the relationship between monthly sales and product categories.

3. Data Modelling using STAR schema

The star schema connects both fact and dimension tables. The facts table represents the quantitative data, while the dimension tables represent descriptive information about the data in the facts table.  Looking at the dataset, the following seven tables Sales Territory data, Reseller data, Date data, Sales Order data, Customer data or Product data serve dimension tables. The Sales table serves as a fact table.
 

Given the .xlsx format, I used Microsoft Excel and Python for data cleaning (e.g. checking for empty values) tasks. The dataset appeared clean. Tableau was used to establish the relationships between the tables automatically.

 
4. Data Visualisation using Tableau

The three dashboards show data for both potential Product and Sales teams. 
First, Sales Information has information on AdventureWorks' overall achievements. 
The second dashboard reflects product information. It offers interactive data exploration between Adventure Works' products and its product categories, as well as the total sales amount. In addition, the products sold are displayed every month. 
The third dashboard shows information on AdventureWorks' most-selling products across clients and their locations. With this information, product or marketing teams can see which product categories are sold to which customer in which city. This could be a starting point for further analysis to analyse what factors determines the sales successfulness and how to optimise this. All dashboards can be filtered based on month, year or the product.
