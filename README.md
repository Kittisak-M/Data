# Job Scraping and Analysis Project

## Project Overview
This project aims to collect job postings data from various job portals, store it systematically, and analyze trends in job postings. The data collected helps identify demand in specific roles, skills, and locations, providing valuable insights for job seekers and companies.

## Data Sources
We are scraping data from the following job websites:
1. **LinkedIn**
2. **Jobsdb** (Completed)
3. **Jobtopgun** (Ongoing)
4. **Jobbkk**
5. **Jobthai**

## Methodology

![Data Pipeline Architecture](https://github.com/Kittisak-M/Data/blob/main/data_pipeline_architecture.png)

### 1. Data Collection
- **Scraping**: Using Python libraries such as BeautifulSoup and Selenium to extract job postings from the websites listed above.
- **Automation**: Scripts are automated to collect fresh data daily using ron jobs (Linux) or Task Scheduler (Windows).

### 2. Data Storage
- **Database/Spreadsheet**: Collected data is stored in a structured format, either in a database (e.g., SQLite, PostgreSQL) or in spreadsheets stored on cloud drives (e.g., Google Drive, OneDrive).
- **Version Control**: The project uses Git for version control, ensuring that the data and scripts are updated and managed efficiently.

### 3. Daily Data Updates
- A Python script runs daily to fetch the latest job postings and update the existing data in the database.
- The process includes data cleaning, deduplication, and formatting to maintain data consistency.

### 4. Data Visualization
- **Power BI**: Used to create interactive dashboards that display job trends, popular job roles, required skills, and more.
- **Looker Studio**: Alternative visualization tool used for data analysis, providing additional flexibility in designing the dashboard.

## Technologies Used
- **Python**: For web scraping, data manipulation, and automation scripts.
- **BeautifulSoup and Selenium**: Libraries used for extracting data from web pages.
- **Git**: For version control, managing updates to scripts and data.
- **Power BI / Looker Studio**: For data visualization and insights generation.
- **Cloud Storage**: Google Drive, OneDrive for storing processed data securely.

## How to Run the Scripts
1. **Clone the Repository**:
   

   


