# API_PowerBI_Demo
API testing experience (Postman), RESTAPI consumption (GET request), ETL and Viz (PBI) demonstration

# API → Power Query → Power BI Demo Project

## Overview
This project demonstrates the full process of consuming a REST API, transforming JSON data using Power Query (M Language), and building an interactive dashboard in Power BI.

## API Source
Public API: https://fakestoreapi.com/products  
Method: GET  
Auth: None  
Format: JSON  

## Tools Used
- Postman (API testing)
- Power BI Desktop
- Power Query (ETL)
- DAX (basic measures)
- GitHub

## ETL Workflow
1. Called API endpoint in Postman
2. Loaded raw JSON into Power Query
3. Flattened nested fields
4. Cleaned and standardized schema
5. Added data types and custom calculated columns
6. Loaded into Power BI model

## Data Model
• Single table  
• Key fields: ProductID, Name, Price, Category, Rating  

## Dashboard Features
- Product count KPI
- Average price KPI
- Price by Category
- Reviews by Category
- Category slicer
- Product detail table

## Files in this Repository
- `API_Demo.postman_collection.json` – Postman GET request
- `API_PowerBI_Demo.pbix` – Dashboard source file
- `API_PowerBI_Demo.pdf` – Dashboard export
- This README.md

## Purpose
This project serves as:
- A portfolio demonstration of API integration skills  
- An example of Power Query JSON ETL  
- A clean Power BI modeling + visualization example

## Project Structure
- `postman_jsonfile_fakeAPIproducts/`
  - Contains Postman collections used for API testing
- `API_PBI_demo.pbix`
  - Power BI dashboard
- `API_PBI_pdf_demo.pdf`
  - Exported Power BI report