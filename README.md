# Oil-Drilling-Supply-Sales-Analysis-Dashboard-in-Power-BI

### Introduction

This project involved the creation of a sales analysis dashboard for a fictitious aftermarket oil & gas drilling supply distributor. It is a modified version of the first full-scale Power BI dashboard I made following the completion of an undergraduate internship for a global machinery manufacturer. This dashboard provides a comprehensive overview of sales, customer, and order data featuring performance metrics and graphical visualizations of sales insights.

**Data Preparation**

<img width="743" alt="image" src="https://github.com/rcfrazier127/Oil-Drilling-Supply-Sales-Dashboard-Power-BI/assets/63532077/48368b98-71c4-45d9-9e39-4bdbc231bdac">

The dataset used in this project was tailored slightly to represent a fictitious oil & gas drilling supply distributor located in Houston, TX that serves customers located in the Houston and Southeast Texas regions. The part and component names were copied from various drilling component part names included in a list online. 

The preparation of the data consisted of standardization of formatting and removal of blank rows and irrelevant columns. Fields in each column were trimmed and extraneous characters/symbols were removed. The column profiling in the Power Query Editor shows 100% validity, no errors, and no blank fields.

### Data Model

![Data Model Screenshot](https://github.com/rcfrazier127/Sales-Analysis-Dashboard-Power-BI/assets/63532077/24312a2a-472d-45df-b389-6df88ecb926b)

A simple star scheme model was used in the creaton of the tables used in this dashboard. This model features a central 'Sales' fact table and 'Customer', 'Order', 'Product', 'Region', and 'Channel' dimension tables. Additionally, a custom date table was created. Presently, this dashboard only utilizes several DAX measures so they are kept in the fact table.

### Dashboard Page

<img width="1564" alt="image" src="https://github.com/rcfrazier127/Oil-Drilling-Supply-Sales-Dashboard-in-Power-BI/assets/63532077/ad67f964-8cc3-4cf9-9c0f-aae767cce80a">

The Sales Analysis Dashboard provides an intuitive and informative overview of sales, product, order volume, and customer data. Featured are slicers allowing the user to filter between different products, customers, cities, and distribution channels to examine a more detailed view of sales performance data and financial metrics. Graphical visuals display sales % growth by customer and product comparison by sales and cost. Time series visuals show sales and gross profit trends over time in addition to order volume, which can help identify seasonal patterns. Sales and order volumes are also broken down according to distribution channel. Featured in the lower left corner is a reset button to revert all slicer selections back to their default settings.
