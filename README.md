# Power BI Dashboard - EuropianStoreAnalysis

![Screenshot 2024-09-30 122636](https://github.com/user-attachments/assets/61d39336-b33b-43ac-af68-27355cb9ff40)

### 1. Overview
#### Purpose:
The EuropianStoreAnalysis dashboard provides insights about the city branch of Europian multi-city store. Report consist spending score as pefamily size, working experience, and profession. It aims to help stores local management to create the offer, and company stakeholder's to make data-driven decisions by visualizing trends, KPIs, and other critical data points.
#### Audience:
This dashboard is intended for use by any of the sales team, store management and stakeholders.
#### Approach:
This project doesn't had database, so the solution is involve several steps:
###### I. Web Scrapping:
This is the process of extracting data from a website or computer screen and importing it into a file or spreadsheet. Here we need to extract data from the software which is used by end client on the store. We use Pyhton script for this process(data_scrapping_notebook.ipynb).
###### II. Data Pre-processing:
This is the process where data health is going to be checked and data treatement will also be done . We use Pyhton script for this process(data_pre_processing_notebook.ipynb). This step contains null check, duplicate check, outliers check, EDA and treatment for all if require.
###### III. Data Visualization:
In this step, dashboard will be created through Microsoft PowerBI with healthy and treated data.

### 2. Data Sources (customers_preprocessed_data.csv)
#### Data provided(Columns):
- CustomerID
- Gender
- Age
- Annual Income ($)
- Spending Score (1-100) [This is calculated by store internal team]
- Work Experience (In years)
- Family Size 
- Profession

### 3. Key Points
#### - Family with the size of "4" is having a highest avg. spending score.
#### - People with the work experience of 2 and 3 years, have the highest avg. spending score than any other class.
#### - Avg. spending score for females with 2 years of experience, is too low than mens with 2 years of experience.
#### - Professionals from engineer, lawyer, marketing, homemakers and nan, having the lowest avg. spending score.
#### - Females with the executive profession and mens from the entertainment are having the highest spending score. 

Each metric provides critical insights into the performance of teams. These metrics are updated regularly and derived from data source provided.

### 4. Instructions for Use
#### Accessing the Dashboard:
- Open EuropianStoreAnalysis.pbix into Power BI Desktop to view the dashboard.
- When dashboard is fully loaded successfully, you can interact with the data.

### 5. Contact Information
For any questions or issues related to the dashboard, please contact:

#### Dashboard Owner/Developer: Siddharth Sahni
#### Email: sidd.sahni3@gmail.com
#### LinkedIn: [Siddharth Sahni](https://www.linkedin.com/in/er-siddharth-sahni-36b227103/)
#### Website: [TheDataMan.github.io/](https://siddharth3.github.io/TheDataMan.github.io/)
