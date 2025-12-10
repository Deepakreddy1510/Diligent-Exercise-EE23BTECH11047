# Diligent – E-Commerce Synthetic Data & Analytics Exercise  
This repository contains my solution for the **Diligent Cursor (A-SDLC) exercise**.  
The goal was to use AI-assisted development to:

1. Generate synthetic e-commerce data (≈5 files)
2. Ingest the generated CSV files into a SQLite database
3. Write SQL queries that join multiple tables and produce meaningful analytics
4. Push the entire workflow to GitHub

This repo demonstrates a clean, reproducible workflow that mirrors a real analytics / data engineering task.

---

##  Repository Structure
```
├── generate_data.py # Python script to generates 5 CSV files
├── ingest_sqlite.py # loads CSVs into a SQLite DB (ecom.db)
├── queries.sql # SQL queries performing multi-table analytics
│
├── customers.csv # Generated customer dataset
├── products.csv # Generated product dataset
├── orders.csv # Generated orders dataset
├── order_items.csv # Generated order item breakdown
├── reviews.csv # Generated product review dataset
│
├── ecom.db # SQLite database created from ingest_sqlite.py
│
├── prompts.txt # The prompts used in github copilot to generate code & SQL
├── requirements.txt # Python dependencies (Faker)
└── README.md # Documentation (this file)
```
