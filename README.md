Cargo Data Analysis (Synthetic Data)

This project simulates and analyzes cargo shipment data using synthetic datasets.

It includes two main parts:



Synthetic Data Generation (Synthetic_data.ipynb)

Uses Python and the Faker library to generate realistic but fake datasets:

Customers (750)

Shipments (25,000)

Transactions

Delivery Feedback

Data includes customer demographics, shipment details, payment info, and feedback.




Data Analysis (Cargo_Data_Analysis.ipynb)

Loads generated CSVs using PySpark

Cleans and transforms data (adds delivery time, customer age, etc.)

Performs analysis on:

Customer types and regions

Shipment trends

Financial transactions

Delivery performance




Run in Colab

Generate data → download CSVs

Upload CSVs in the analysis notebook

