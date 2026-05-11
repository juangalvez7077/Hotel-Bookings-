#  Hotel Booking Cancellation Analysis — ETL Pipeline

**Corporate Intelligence Project | UFV Madrid | 2025–2026**

---

##  Overview

This repository contains the full ETL pipeline for the hotel booking cancellation analysis, developed as part of the Business Intelligence project.

The pipeline transforms the raw *Hotel Booking Demand* dataset into a clean, analytically enriched dataset of **87,144 records and 44 variables**, ready for direct ingestion into Power BI.

---

##  Run in Google Colab

Click the button below to open and run the notebook directly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/juangalvez7077/Hotel-Bookings-/blob/main/Hotel_Bookings_ETL_code.ipynb)

> **Requirement:** You will need to upload the `hotel_bookings.csv` file when prompted by the notebook.

---

##  Pipeline Structure

| Step | Description |
|------|-------------|
| **Step 1 – Extract** | Load the original dataset (119,390 records, 32 columns) |
| **Step 2 – Quality Analysis** | Detection of nulls, duplicates, outliers and invalid records |
| **Step 3 – Data Cleaning** | Drop duplicates, impute missing values, fix data types |
| **Step 4 – Feature Engineering** | Creation of 11 new variables: `total_nights`, `estimated_revenue`, `risk_score`, etc. |
| **Step 5 – Validation** | Final dataset verification before loading |
| **Step 6 – Load** | Export to Excel (`.xlsx`) ready for Power BI |

---

##  Pipeline Results

| Metric | Value |
|--------|-------|
| Original records | 119,390 |
| Records after cleaning | 87,144 |
| Final columns | 44 |
| Cancellation rate | 27.52% |
| Total estimated revenue | EUR 34,312,805 |
| Revenue lost (cancellations) | EUR 11,427,753 |



##  Repository Structure


Hotel-Bookings/
│── Hotel_Bookings.csv              
├── Hotel_Bookings_ETL_code.ipynb   
└── README.md                        




##  Authors

Project developed for the Corporate Intelligence course — Universidad Francisco de Vitoria (UFV Madrid) by Juan Lantero, Juan Gálvez, Galo Prensa and Ignacio Evangelista.
