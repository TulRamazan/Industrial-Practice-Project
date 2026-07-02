# NoSQL Database Engineering and ETL Pipeline

This repository contains the technical implementation and research developed during the Industrial Practice at **TLab Technologies**. The project focuses on designing scalable NoSQL database structures, implementing server-side validation rules, and building automated ETL (Extract, Transform, Load) pipelines for corporate data management.

## 👤 Developer Information
* **Name:** Tulentay Ramazan Erboluly
* **University:** Astana IT University
* **Major:** Big Data Analysis (Group BDA-2407)

---

## 🚀 Project Overview
The core objective of this project was to establish a secure, validated, and highly optimized non-relational database infrastructure using MongoDB Atlas and Python. The system processes simulated corporate telemetry and structured documentation, ensuring strict data integrity before storage.

### Key Features
* **Automated ETL Pipeline:** Seamless data ingestion, cleaning, and formatting using Python and Pandas.
* **Server-Side Validation:** Implementation of strict `$jsonSchema` rules inside MongoDB to enforce data types, required fields, and structural constraints.
* **Advanced Aggregation:** Complex multi-stage aggregation pipelines for analytical reporting and real-time statistics generation.
* **Security & Testing:** Integrated cryptographic checks, data masking simulations, and structured authentication logic executed within a secure laboratory pipeline (`run_laboratory_testing_pipeline`).

---

## 🛠️ Tech Stack
* **Database:** MongoDB Atlas (NoSQL)
* **Language:** Python 3.x
* **Libraries:** PyMongo, Pandas
* **Environment:** Jupyter Notebook / Production Python Scripts

---

## 📂 Repository Structure
```text
├── README.md                  # Project documentation (this file)
├── requirements.txt           # Required Python libraries
├── .gitignore                 # Python and environment exclusion rules
├── src/
│   └── telemetry_pipeline.py  # Production ETL script and laboratory pipeline
└── notebooks/
    └── Week3_Analysis.ipynb   # Jupyter Notebook with Task 9 and aggregation tests
