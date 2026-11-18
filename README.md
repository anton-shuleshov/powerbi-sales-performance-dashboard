Sales Performance Dashboard | Power BI

A business intelligence portfolio project exploring sales performance, profitability, customer activity, discounting, and regional trends through an interactive Power BI report.

Dashboard preview

Sales Performance Dashboard

Project overview

The dashboard brings together sales transactions and reference data to provide a consolidated view of commercial performance. It is designed to help users explore revenue, gross profit, discount levels, customer activity, and differences across regions and business divisions.

Key performance indicators

|KPI                      |Dashboard value|
|-------------------------|--------------:|
|Total Sales              |20.82M         |
|Gross Profit             |9.15M          |
|Gross Profit Margin      |43.9%          |
|Customers                |312            |
|Quantity Sold            |326.63K        |
|Total Discount           |12.29M         |
|Discount Rate            |37.1%          |
|Sales per Item           |63.74          |
|Average Sale per Customer|66.72K         |
|Average Discount         |1.84K          |

Values shown are from the saved dashboard view and may change with filters. Monetary units follow the source dataset; no currency is assumed here.

Report features

● Monthly sales trend

● Sales distribution by region

● Sales by business division

● Top 10 customers by sales amount

● Country map for geographic context

● Interactive filters for region, division, and year

Data sources

The report uses five educational Excel datasets stored in Data/:

|File                  |Purpose                                  |
|----------------------|-----------------------------------------|
|`SALESDATA.xlsx`      |Sales transactions and financial measures|
|`CUSTOMERS.xlsx`      |Customer reference information           |
|`CUSTOMERADDRESS.xlsx`|Customer address and country information |
|`REGION.xlsx`         |Region lookup data                       |
|`DIVISION.xlsx`       |Business division lookup data            |

The data model connects sales, customer, address, region, and division information using the relevant identifiers.

Tools and skills demonstrated

● Power BI Desktop: interactive dashboard design and reporting

● Power Query: importing, cleaning, and typing Excel data, including date fields

● Data modeling: relationships across transaction and lookup tables

● DAX: measures and KPIs for sales and profitability

● Data visualization: trend, category, customer, and geographic views

Repository files

|File                                                                  |Description                                                                                    |
|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
|[`Sales_Performance_Portfolio.pbix`](Sales_Performance_Portfolio.pbix)|Power BI Desktop report; open with Power BI Desktop                                            |
|[`Sales_Performance_Portfolio.pdf`](Sales_Performance_Portfolio.pdf)  |Static PDF export                                                                              |
|[`dashbord.png`](dashbord.png)                                        |Dashboard screenshot                                                                           |
|[`Sales_Performance_Portfolio.pbip`](Sales_Performance_Portfolio.pbip)|Power BI Project entry file; requires its associated project folders to be usable independently|
|[`Data/`](Data/)                                                      |Educational Excel source files                                                                 |

Opening the report: Download the .pbix file and open it in Power BI Desktop. To refresh data, update the Excel source paths to the location of the downloaded Data folder on your computer.

Note on the map: The country map is included as geographic context. Sales-by-country markers were not fully validated in the published view, so the map should not be interpreted as a verified country-level sales comparison.

Author

Anton Shuleshov
Data Analytics & Business Intelligence Portfolio
