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

  

https://private-user-images.githubusercontent.com/83348192/410763640-6ff35a92-5273-44f2-a82d-deee610ab8f7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mzg5MDQzMzUsIm5iZiI6MTczODkwNDAzNSwicGF0aCI6Ii84MzM0ODE5Mi80MTA3NjM2NDAtNmZmMzVhOTItNTI3My00NGYyLWE4MmQtZGVlZTYxMGFiOGY3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAyMDclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMjA3VDA0NTM1NVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM5OWI5NzM2YmMzNDdjNTQyMDJjNmZmZWNiNTFjODk2MGMwOWI0NjQzMmExZGY0YjBjOWM3OTFlMTlmOTdkNDAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.yPMiDpxv7DL8FwtfBst8-2YEge-3apm63nGznY--T2g
