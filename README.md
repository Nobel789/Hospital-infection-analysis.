# Hospital Infection Pattern Analysis

## Overview
This repository contains an end-to-end data analysis project focused on detecting and reporting hospital-acquired infection (HAI) patterns. The project demonstrates the complete data lifecycle: analyzing raw patient records, aggregating data into summaries, and visualizing the results in a management-level dashboard.

## Project Assets

### 📓 Analysis Notebook
* **`Hospital_Ward_Infection_Pattern_Detection.ipynb`:** A Jupyter Notebook detailing the data analysis process. This includes exploratory data analysis (EDA), pattern detection across different hospital wards, and statistical summaries of infection rates.

### 📁 Datasets (CSV)
* **`hospital_infection_patients_150.csv`:** A granular, synthetic dataset containing 150 patient records, including variables like department, length of stay, prevention bundles, and expected vs. actual infection rates.
* **`hospital_infection_summary.csv`:** An aggregated dataset summarizing the raw patient data to highlight overall ward performance, raw infection rates, and variances from benchmark standards.

### 📊 Dashboard
* **`Hospital_infection_rate_dashboard.pdf`:** A static export of the final visualization dashboard. This report translates the data from the CSV summaries into actionable insights for hospital administration and quality assurance teams.

## How to Use
1. **Explore the Code:** Open the Jupyter Notebook to review the Python logic used for pattern detection and data summarization.
2. **Review the Results:** Open the PDF dashboard to see the final reporting structure.
3. **Analyze the Data:** The CSV files can be loaded into Pandas, R, or any BI tool to replicate the analysis or build new visual models.

> **Disclaimer:** All data within this repository is strictly synthetic and created for educational demonstration purposes. It does not contain real patient health data or Protected Health Information (PHI).
