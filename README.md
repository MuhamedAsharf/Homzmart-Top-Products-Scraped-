# Homzmart-Top-Products-Scraped-
Project to scrape top-selling products from Homzmart using Python and Power BI.
--

### 1. Phase 1: Data Collection (Web Scraping)

Data collection was not straightforward. I built a custom scraper using Python with the "Selenium" and "Beautiful Soup" libraries.

The Challenge: The primary hurdle was the dynamic nature of the website and the highly unstructured data.
The Solution: This required precise programming logic to correctly parse complex data points like "Sizes and Number of Pieces," which were written in completely different formats from one product to the next. I also implemented logic to handle site "pagination" to ensure all product data was collected.

### 2. Phase 2: ETL & Data Transformation (Data Cleaning & Engineering)

Raw data is rarely ready for analysis. Using "Power Query", I performed intensive ETL (Extract, Transform, Load) operations.

Data Cleaning: This involved more than just removing nulls or standardizing formats (e.g., "Black and White" vs. "White and Black").
Feature Engineering: I engineered new calculated columns, such as "Price Category," to segment products. This allows for deeper and more meaningful comparative analysis.

### 3. Phase 3: Analysis & Power BI Dashboard

I designed an interactive Power BI dashboard that doesn't just display numbers—it tells the data's story and answers key business questions.

Deep Analysis: The dashboard features a "Scatter Plot" analyzing the relationship between Price and Rating, distribution of products across Price Categories, and identification of "Top/Bottom N" performing products.
Enhanced User Experience: To make the dashboard highly interactive, I added custom "tooltips" that display the product's image (fetched from the scraped URL) on hover, along with smart, dynamic filters.

---

### Tools & Technologies Used

* Data Scraping: ython (Selenium, Beautiful Soup)
* ETL & Transformation:Power Query
* Visualization & Analysis:Power BI (DAX, M Query)

