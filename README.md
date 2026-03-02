End-to-End Netflix Content Strategy Analysis: From Raw Data to Business Insights

Business Objective
The objective of this project was to analyze Netflix’s content catalog to understand:
•	What type of content the platform prioritizes
•	Growth trends over time
•	Genre investment patterns
•	Global production distribution
•	Audience targeting strategy
•	Catalog freshness and release delay
The goal was to simulate stakeholder-driven analysis and provide decision-support insights.

Problem Definition & Analytical Objectives
Before writing SQL queries, business questions were framed from a non-technical stakeholder perspective:
•	Which type has the highest collection?
•	In which year were the most titles added?
•	Is Netflix shifting toward TV Shows?
•	Which month sees peak releases?
•	Which genre dominates the platform?
•	Which country produces the most content?
•	Which rating category dominates?
•	What is the average delay between release and platform addition?
•	In 2020, which type dominated releases?
This structured questioning ensured analysis remained business-oriented rather than purely technical.

Data Cleaning & Feature Engineering (Power Query)
Data preprocessing included:
•	Importing and validating dataset
•	Sorting titles
•	Removing unwanted characters
•	Standardizing capitalization
•	Converting date formats
•	Splitting date_added into:
o	month_added
o	year_added
•	Creating new column:
o	content_age = year_added - release_year
•	Creating derived category:
o	content_category (New, Recent, Mid Catalog, Old Library)
These transformations enabled deeper strategic analysis.

SQL Analysis
SQL queries were designed to answer stakeholder-level questions:
•	Content distribution by type
•	Yearly growth trends
•	Monthly release patterns
•	Genre ranking
•	Country dominance
•	Rating distribution
•	Average content age

Python Exploratory Analysis
Python visualizations were used to:
•	Identify growth spikes
•	Analyze content age distribution
•	Visualize genre investment
•	Compare audience segments
•	Detect release patterns
Dashboard Development
An executive dashboard was built in Power BI featuring:
•	KPI cards (Total Titles, Movies, TV Shows, Top Genre, Top Country, Average Content Age)
•	Growth trend visualization
•	Genre investment ranking
•	Audience rating distribution
•	Content freshness analysis
The dashboard was designed using Netflix-themed visual hierarchy and strategic color emphasis.
Key Findings
•	Movies dominate the catalog.
•	TV Shows are gradually increasing.
•	2016–2019 marked aggressive expansion.
•	Drama is the top genre.
•	United States leads content production.
•	TV-MA rating dominates (mature audience focus).
•	Average release delay is ~6 years.
•	New content dominates catalog freshness
Learning Outcomes
This project strengthened skills in:
•	Data cleaning & transformation
•	SQL business querying
•	Feature engineering
•	Data visualization
•	Dashboard design principles
•	Business storytelling
It reinforced the complete analytics lifecycle from data ingestion to executive reporting.
