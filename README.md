Swiggy Sales Analysis Dashboard (Excel)

An interactive Excel dashboard analysing 197,430 Swiggy order records across Indian cities, covering sales, ratings, order value, food type, and time-based trends (January to August 2025).
Table of Contents
Project Objective
Dataset
Key Metrics
Key Insights
Tools and Techniques
Workbook Structure
How to Use
Limitations
Author
Project Objective

To convert raw Swiggy order data into a decision-ready dashboard that answers:

Which cities and states generate the most revenue?
Which days and months drive peak sales?
How do vegetarian and non-vegetarian orders compare?
How do sales and order volume perform quarter over quarter?
Dataset
Attribute	Detail
Records	197,430
Period	January to August 2025
Key fields	State, City, Order Date, Day, Quarter, Week, Restaurant Name, Location, Category, Dish Name, Price (INR), Rating
Derived field	Food Type (Veg / Non-Veg), created using nested IF with SEARCH
Key Metrics
Metric	Value
Total Sales	INR 53.0M
Total Orders	197.43K
Average Rating	4.34
Average Order Value	INR 268.51
Key Insights
Veg leads Non-Veg: Vegetarian items account for 63% of sales (INR 33.3M) versus 37% for Non-Veg (INR 19.7M).
Bengaluru is the top market: INR 5.5M in sales, nearly double the next city, Lucknow (INR 3.1M).
Saturday is the peak day: INR 7.78M, while Tuesday is the lowest at INR 7.36M.
Monthly trend: Sales peak in January, May and August at roughly INR 6.8M, with a dip in February.
Quarterly performance: Q1 (INR 19.7M) and Q2 (INR 19.9M) are nearly equal. Q3 covers only July and August.
Tools and Techniques
Microsoft Excel
Data cleaning and structuring (Excel Tables)
Pivot Tables and Pivot Charts
Slicers (Month, Category, Restaurant Name)
Nested IF and SEARCH formulas for Veg / Non-Veg classification
KPI cards, geographic map chart, conditional formatting
Veg / Non-Veg Classification Logic

How to Use
Download Swiggy_project.xlsx from the data/ folder (or from the release link below).
Open it in Microsoft Excel 2016 or later.
Go to the Dashboard sheet.
Use the slicers (Month, Category, Restaurant Name) to filter all visuals.
If values do not refresh, go to Data > Refresh All.
Limitations
Data covers January to August only, so Q3 is incomplete and not directly comparable with Q1 and Q2.
Veg / Non-Veg classification is keyword based and may misclassify unusual dish names.
Author

Mayank_Bachchani Data Analyst | LinkedIn - www.linkedin.com/in/mayank-bachchani-b703b4346 | Email - mayank.b.analytics@gmail.com

If you found this project useful, consider giving it a star.

Each dish name is searched for non-veg keywords (chicken, egg, fish, mutton, prawn, biryani, kabab, kebab, and similar). If any keyword matches, the item is labelled Non-Veg; otherwise Veg.
