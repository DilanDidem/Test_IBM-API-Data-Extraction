# 📊 IBM Lab Project: Accessing Data Using APIs

This project optimized a laboratory exercise from the **IBM Data Analyst Professional Certificate**. It demonstrates API data retrieval, payload filtering, and multi-format data exporting using Python.

## 🎯 Objective
* **Goal:** Quantify job openings across targeted technologies and geographic locations.
* **Task:** Extract and aggregate job posting counts from the API data source.

## 📂 Dataset & Schema
The project processes a raw JSON dataset (`jobs.json`) structured with the following keys:
* `Job Title`
* `Job Experience Required`
* `Key Skills` *(The column scanned for technology analysis)*
* `Role Category`
* `Location` *(The column scanned for geographic analysis)*
* `Functional Area`
* `Industry`
* `Role`

> **Note:** The raw `jobs.json` file is included in this repository for local testing and permanence.

## 📦 Project Deliverables
The pipeline processes the raw input and generates three structured outputs:
* `job_skills.csv` — Job counts mapped by technology keywords.
* `job_locations.csv` — Job counts mapped by targeted cities.
* `job_skills.xlsx` — Multi-sheet Excel report built via `openpyxl`.

---

## 📑 Portfolio Disclaimer
This repository serves as a portfolio piece showcasing data pipeline construction, API management, and optimization practices from the IBM curriculum.

## 🤝 Acknowledgements
Special thanks to **IBM** and the program instructors for the foundational curriculum and dataset that inspired this project.
