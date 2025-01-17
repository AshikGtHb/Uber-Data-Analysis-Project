# Uber-Data-Analysis-Project
Modern data Engineering project using Google Cloud services, open-source tools, and Python.

<h2>Project Overview</h2>
Data Source: Uber dataset was used.
Data Model: Fact table and multiple dimension tables were built.
Pipeline Tool: Open-source tool Mage was used for data loading, transformation and exporting to Google's BigQuery.

Google Cloud Platform (GCP):
Data was stored in Google Cloud Storage.
Data transformations were done in Python via Mage. SSH server in Google Cloud was used 
Results are loaded into BigQuery, GCP's data warehouse.
Dashboard Creation: The final dashboard is built using Google Data Studio.

What we did, step-by-step:
- Created fact and dimension tables for better analysis.
- Foreign keys link dimensions to the fact table.
- GCP BigQuery: Creating datasets and tables for storing transformed data.
- Generate a JSON key file for authentication.
- In Mage, updated yaml configuration with service account details (e.g., project ID, private key, email, etc.).
- Used Transformation logic to retrieve tables, process and load them into BigQuery.
- Designed interactive dashboards using Google Data Studio.
