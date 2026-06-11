# Data Analyst Job Market Analysis

## Overview

This project focuses on analyzing the Indian job market for data-related roles such as Data Analyst, Data Scientist, Business Analyst, and Data Engineer.

The goal of this project is to explore hiring trends, salary patterns, location-based opportunities, and in-demand technical skills using real-world job posting data. The project involves extensive data cleaning, preprocessing, feature engineering, skill normalization, and exploratory data analysis (EDA) to prepare the dataset for deeper analytical insights and dashboard creation.

---

## Project Objectives

* Analyze hiring trends for data-related roles in India
* Identify the most in-demand technical skills
* Explore salary distributions across different roles
* Standardize messy real-world job posting data
* Prepare clean datasets for visualization and dashboarding
* Build a scalable analytics workflow for future extensions

---

## Tech Stack

### Languages & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Tools

* Jupyter Notebook
* Git
* GitHub
* Power BI *(planned)*

### Future Integrations

* SQL
* Power BI Dashboard
* Web Scraping / APIs
* Advanced Analytics & Machine Learning

---

## Dataset Information

The dataset consists of job postings related to data-focused roles in India.

### Included Roles

* Data Analyst
* Data Scientist
* Business Analyst
* Data Engineer
* Other related analytical roles

### Data Challenges Handled

* Missing company names
* Inconsistent salary formats
* Noisy and duplicate skill entries
* Location normalization
* Role standardization
* Irrelevant and low-frequency skill filtering

---

## Data Cleaning & Preprocessing

### Company Name Handling

Some job postings did not disclose company names. These were retained and labeled as `Not Disclosed` to avoid unnecessary data loss.

### Location Normalization

Location values were standardized by:

* correcting typos,
* normalizing common variants,
* grouping locations into metro-level regions such as:

  * Mumbai
  * Delhi NCR
  * Bangalore
  * Hyderabad

This improves consistency for geographic analysis and Power BI visualization.

### Salary Standardization

Salary information appeared in multiple inconsistent formats such as:

* `₹6–10 LPA`
* `5 Lakh`
* `3–5 LPA`

These were standardized into:

* `salary_min`
* `salary_max`
* `salary_mid`

All salary values were converted into numeric LPA format for quantitative analysis.

### Skills Processing

Skills were:

* cleaned,
* normalized,
* standardized,
* exploded into row-level entries,
* filtered for relevance.

An exploded skills dataset was created to support skill-frequency and demand analysis.

---

## Project Workflow

1. Raw dataset collection
2. Data understanding and initial cleaning
3. Salary preprocessing and normalization
4. Skill cleaning and normalization
5. Dataset explosion for skill-level analysis
6. Role narrowing and filtering
7. Creation of processed analytical datasets
8. Exploratory Data Analysis (EDA)
9. Dashboard preparation *(ongoing)*

---

## Repository Structure

```text
01_data/
│
├── raw_jobs.csv

02_notebooks/
│
├── Initial cleaning notebooks
├── Skills preprocessing notebooks
├── Role filtering notebooks
└── EDA preparation notebooks

03_intermediate_work/
│
├── Intermediate datasets
├── Experimental preprocessing outputs
└── Workflow backup files

04_processed_data/
│
├── Final cleaned datasets
└── Exploded skills datasets

05_Final_EDA/
│
├── EDA notebooks
├── Final analytical datasets
└── Visualization preparation
```

---

## Current Project Status

### Completed

* Data cleaning
* Feature engineering
* Salary preprocessing
* Skill normalization
* Role filtering
* Exploded skills dataset creation
* EDA dataset preparation

### Ongoing

* Exploratory Data Analysis
* Visualization building
* Dashboard development

### Planned

* Power BI dashboard
* SQL integration
* Automated data collection
* Advanced analytics
* Machine learning-based insights

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Real-world data cleaning
* Handling inconsistent datasets
* Feature engineering
* Data preprocessing pipelines
* Skill normalization techniques
* Exploratory Data Analysis
* Git & GitHub workflow
* Structuring analytics projects

---

## Future Scope

Planned future enhancements include:

* Interactive Power BI dashboard
* SQL database integration
* Automated data collection pipelines
* Real-time job market tracking
* Machine learning-based trend prediction
* Skill recommendation insights

---

## Author

Umang Chourasia

Aspiring Data Analyst | Data Science Enthusiast
