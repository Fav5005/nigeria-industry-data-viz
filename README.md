# Nigeria Industry Analysis Dashboard

## Table of Contents
* [Project Overview](#project-overview)
* [Data Sources](#data-sources)
* [Tools Used](#tools-used)
* [Data Cleaning and Preparation](#data-cleaning-and-preparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Project Features](#project-features)
* [Key Insights](#key-insights)
* [References](#references)

---

## Project Overview
This project aims to provide insights into the **industrial landscape of Nigeria** by analyzing a dataset of major companies. The project uses an **automated pipeline** to extract, clean, and visualize data to help users explore corporate trends. Specifically, this dashboard helps in:

- **Identifying** the total number of companies across various sectors.
- **Understanding** the distribution of company ownership (Private vs. State-owned).
- **Exploring** the historical timeline of company foundations in Nigeria.
- **Visualizing** the geographical concentration of corporate headquarters.

<img width="361" height="284" alt="Visualization in Python" src="https://github.com/user-attachments/assets/0d3c5cdb-b3bb-436c-bd67-d4b903681dff" />

---

## Data Sources
**Nigerian Company Data**: The dataset used for this analysis was sourced from **Wikipedia**. It contains information about major Nigerian firms including:
* Company Name
* Industry/Sector
* Ownership Status (Private/State)
* Foundation Year
* Headquarters Location

---

## Tools Used
* **Python**: Core programming language for data processing.
* **BeautifulSoup**: Used for automated web scraping and data extraction.
* **Pandas**: Used for data manipulation and cleaning.
* **Matplotlib & Seaborn**: Used for creating professional dark-themed visualizations.
* **Jupyter Notebook**: The environment used for end-to-end development.

---

## Data Cleaning and Preparation
In the initial data preparation, I performed the following tasks:
1. **Web Scraping**: Automating the extraction of table data from Wikipedia.
2. **Handling Missing Values**: Identifying and managing incomplete foundation years or location data.
3. **Data Standardization**: Standardizing ownership labels (P to Private, S to State) and industry names.
4. **Type Conversion**: Converting foundation years into numeric format for timeline analysis.

---

## Exploratory Data Analysis
EDA involved exploring key trends in the dataset, including:
* Distribution of companies by **Industry**.
* **Ownership status** breakdown using standardized pie charts.
* Company **foundation trends** over the last century.
* Top 5 **Business Hubs** in Nigeria by headquarters count.

---

## Project Features
The automated Python pipeline contains:
* **Web Scraper**: A reusable script to pull fresh data from web tables.
* **Automated Cleaning**: Scripted logic to handle data inconsistencies without manual intervention.

---

## Key Insights
* **Private Sector Growth**: Over **84%** of the companies analyzed are privately owned, showing a dominant private enterprise culture.
* **Economic Hubs**: **Lagos** remains the primary nerve center for Nigerian industry, followed closely by regional hubs like Ikeja.
* **Industrial Boom**: There is a visible surge in company foundations starting from the **1990s**, coinciding with various economic reforms.

---

## References
* **Dataset Source**: [List of companies of Nigeria](https://en.wikipedia.org/wiki/List_of_companies_of_Nigeria) (Sourced from Wikipedia).
