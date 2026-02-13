# 🏦 Banking Rate Processing Automation — IDE Test Case (UiPath)

## 📌 Overview

This project is a banking automation proof-of-concept developed using UiPath as part of a technical assessment for IDE.

The automation processes two structured but complex PDF files containing financial rate data (FX Rates and Revaluation Rates). The workflow extracts data from both sources, performs string manipulation and JSON-based transformation, and generates a unified output sheet while preserving data integrity.

The primary goal is to demonstrate how Robotic Process Automation (RPA) can automate financial data processing without damaging or altering original values.

---

## 🎯 Objectives

* Extract structured data from multiple PDF documents.
* Normalize and transform extracted data using string manipulation.
* Convert extracted information into JSON format.
* Merge datasets safely without data loss.
* Generate a unified structured output file.

---

## 🚀 Features

* Automated PDF data extraction
* String parsing and normalization
* JSON-based data processing and mapping
* Safe data merging logic
* Data integrity preservation
* Automated output generation

---

## 🛠️ Technologies Used

* UiPath Studio
* Document Understanding Activities
* String Manipulation Techniques
* JSON Parsing & Serialization
* DataTables
* Excel Automation

---

## 📂 Input Data

The automation processes:

* FX Rates PDF (daily currency exchange rates)
* Revaluation Rates PDF

These files contain structured financial data that must be combined into a single dataset without altering original numeric values.

---

## ⚙️ Workflow Logic

1. Load both PDF documents.
2. Extract relevant currency and rate information.
3. Perform string manipulation to normalize extracted text.
4. Convert structured data into JSON objects.
5. Map and merge datasets based on currency identifiers.
6. Validate merged data to ensure no loss or corruption.
7. Generate unified output sheet.

---

## ▶️ How to Run

1. Open project in UiPath Studio.
2. Restore dependencies if prompted.
3. Place input PDFs in configured folder.
4. Run `Main.xaml`.

---

## 🧠 Business Value

* Demonstrates automation for financial data processing workflows.
* Eliminates manual data merging tasks.
* Reduces risk of human error in financial reporting.
* Shows integration of RPA with structured data formats (JSON).

---

## 🔐 Data Privacy Notice

This project is a technical demonstration only. No confidential banking information is included.

---

## 👨‍💻 Author

Mohamed Sameh
Computer Science Student | RPA & Automation Enthusiast
