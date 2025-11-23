**ETL Pipeline for Banggood.com - Product Data Extraction (5 Categories)**

This repository implements an ETL (Extract, Transform, Load) pipeline designed to extract, transform, and load product data from Banggood.com, a leading Chinese e-commerce platform. Currently, the pipeline targets five specific product categories spanning different domains.

**Features:**

- Extracts product information from Banggood's website.
- Transforms raw data into a structured format for analysis.
- Loads the data into a MySQL database for further processing and querying.

**Technologies Used:**

The ETL pipeline is implemented in Python and leverages the following libraries and tools:

- **Selenium** – for web scraping, particularly for rendering dynamic content (JavaScript-driven HTML).
- **BeautifulSoup** – for parsing and extracting data from HTML.
- **Pandas** – for data transformation and manipulation.
- **Matplotlib** – for visualizing the data.
- **PyMySQL** – for database connectivity and data loading.

**Prerequisites:**

Before running this application, ensure that you have the following installed:

Python (preferably Python 3.x)

An Integrated Development Environment (IDE) for Python (e.g., VSCode, PyCharm, etc.)

**Application Workflow:**
The pipeline is divided into five distinct sub-tasks: from data extraction to data analysis. The process flow is summarized in the following diagram:

<img width="575" height="734" alt="image" src="https://github.com/user-attachments/assets/532dcc5d-3d16-405d-a0ed-a0552bcbd242" />

The pipeline uses Selenium to scrape dynamic content from Banggood.com, as the product data is rendered via JavaScript.
