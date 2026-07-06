# Mortgage-Servicing-AI-Assistant
Build an AI-powered application where a mortgage servicing analyst can ask questions such as:
"Show loans that are over 90 days delinquent." 
"Summarize escrow shortages for California." 
"Which borrowers missed the last three payments?"
"What is the total unpaid principal balance by investor?" 
"Explain why Loan 100045 is high risk."



# Repository Structure

Mortgage-Servicing-AI-Assistant/
│
├── README.md
│
├── datasets/
│   ├── borrower.csv
│   ├── loan.csv
│   ├── payment_history.csv
│   ├── escrow.csv
│   ├── property.csv
│   ├── delinquency.csv
│
├── sql/
│   ├── 01_database.sql
│   ├── 02_tables.sql
│   ├── 03_load_data.sql
│   ├── 04_views.sql
│   ├── 05_cortex.sql
│
├── snowpark/
│   ├── data_loader.py
│   ├── transformations.py
│
├── streamlit/
│   ├── app.py
│
├── cortex/
│   ├── semantic_model.yaml
│
├── screenshots/
│
└── docs/
    ├── Architecture.png
    ├── ERDiagram.png
