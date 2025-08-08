# Cargo Data Analysis (Synthetic Data)

[![Open Synthetic Data in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yed-hu/Projects/blob/main/Synthetic_data.ipynb)
[![Open Analysis in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yed-hu/Projects/blob/main/Cargo_Data_Analysis.ipynb)

This project simulates and analyses end to end cargo shipment data using synthetically generated records.  
It demonstrates the process of generating, cleaning, transforming, and analyzing logistics related datafrom customer details to shipment performance using tools like **Python**, **Pandas**, and **Apache Spark**.

   

## Project Components

### 1. Synthetic Data Generation (`Synthetic_data.ipynb`)
Leveraging the `Faker` library and Python's built in modules, this notebook creates realistic but fictional datasets mimicking a logistics/cargo business:

  **Customers**: 750 unique records with personal and demographic details (e.g., name, contact, occupation, region, etc.)
  **Shipments**: 25,000 shipment records including weight, volume, dates, provider, service type, and status
  **Transactions**: Financial records linked to each shipment, with payment methods and statuses
  **Feedbacks**: Delivery feedback and customer complaints including ratings and issue types

   

### 2. Data Analysis with PySpark (`Cargo_Data_Analysis.ipynb`)
This notebook loads the generated CSV files into **PySpark DataFrames** for scalable analysis:

  Schema inspection and data cleaning (e.g., removing redundant columns, type conversions)
  Enrichment with derived fields (e.g., customer age, delivery time in days)
  Group by aggregations and trend analysis:
    Customer demographics by nationality, occupation, and type
    Shipment trends by region, delivery time, and destination
    Financial insights such as total transaction value (in crores)
    Delivery performance metrics and complaint analysis

   



