# Oil-Drilling-Supply-Sales-Analysis-Dashboard-in-Power-BI

### Introduction

This project involved the creation of a sales analysis dashboard for a fictitious aftermarket oil & gas drilling supply distributor. It is a modified version of the first full-scale Power BI dashboard I made following the completion of an undergraduate internship for a global machinery manufacturer. This dashboard provides a comprehensive overview of sales, customer, and order data featuring performance metrics and graphical visualizations of sales insights.

**Data Preparation**

The dataset used in this project was tailored slightly to represent a fictitious oil & gas drilling supply distributor located in Houston, TX that serves customers located in the Houston and Southeast Texas regions. The part and component names were copied from various drilling component part names included in a list online. 

The preparation of the data consisted of standardization of formatting and removal of blank rows and irrelevant columns. Fields in each column were trimmed and extraneous characters/symbols were removed. 

<img width="743" alt="image" src="https://github.com/rcfrazier127/Oil-Drilling-Supply-Sales-Dashboard-Power-BI/assets/63532077/48368b98-71c4-45d9-9e39-4bdbc231bdac">

The column profiling in the Power Query Editor shows 100% validity, no errors, and no blank fields.

### Data Model

A simple star scheme model was used in the creaton of the tables used in this dashboard. This model features a central 'Sales' fact table and 'Customer', 'Order', 'Product', 'Region', and 'Channel' dimension tables. Additionally, a custom date table was created. Presently, this dashboard only utilizes several DAX measures so they are kept in the fact table.

![Data Model Screenshot](https://github.com/rcfrazier127/Sales-Analysis-Dashboard-Power-BI/assets/63532077/24312a2a-472d-45df-b389-6df88ecb926b)

### Dashboard



<img width="1564" alt="image" src="https://github.com/rcfrazier127/Oil-Drilling-Supply-Sales-Dashboard-Power-BI/assets/63532077/b4d0f085-9fa6-4bf5-a616-9f3d1a2978f8">
