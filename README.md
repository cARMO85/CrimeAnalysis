# Crime Analysis Using Big Data

**Author:** Paul Carmody  
**Date:** March 2025

## Overview

This project applies modern data analysis and big data techniques to examine crime trends in the UK, focusing on claims made in the 2018 documentary *Ross Kemp and the Armed Police*. Using a cloud-based ETL pipeline and statistical modelling, the project challenges public narratives with empirical evidence and demonstrates scalable analytics on real-world data.

---

## Objectives

- **Evaluate media claims** on violent crime trends using open UK crime datasets (~19 million records)
- Build a **scalable big data pipeline** for data ingestion, cleaning, and analysis in the cloud (Azure + PySpark)
- Apply **statistical tests and machine learning** to uncover true patterns and associations
- **Visualise insights** and communicate findings clearly for technical and non-technical audiences

---

## Key Technologies

- **Azure IaaS:** Cloud infrastructure for scalable processing
- **Apache Spark / PySpark:** Distributed data processing (ETL & analytics)
- **Python (Pandas, Matplotlib, Seaborn):** Data analysis & visualisation
- **Statistical analysis:** t-tests, Pearson correlation, linear regression
- **Jupyter Notebook:** Interactive data exploration and reporting

---

## Workflow

1. **Data Acquisition:**  
   Downloaded UK Home Office street-level crime data (2010–2021, ~19M rows) and population data (LSOA).

2. **Data Engineering:**  
   - Built ETL pipeline with PySpark on Azure to handle large volumes efficiently  
   - Cleaned, joined, and standardised datasets for analysis

3. **Analysis:**  
   - **Time-series analysis:** Trends in burglary over time  
   - **Geospatial analysis:** Burglary rates per city and per capita  
   - **Statistical tests:**  
     - T-tests (trend analysis, regional comparisons)  
     - Correlation & regression (firearms vs. drug crime)

4. **Visualisation:**  
   - Rolling average and line/bar charts for trends and city comparisons  
   - Dual-axis charts for exploring relationships between crime types

5. **Findings & Reporting:**  
   - Produced a detailed, fully referenced report debunking common media claims  
   - Insights include:  
     - Burglary rates have declined overall, contrary to media claims  
     - Birmingham does **not** have the highest burglary rate per capita  
     - No strong statistical link between firearm and drug offences

---

## Results

- **Scalable, cloud-based analytics** on 19M+ rows
- **Robust, reproducible code** for big data ETL, analysis, and visualisation
- **Statistical evidence** that challenges and clarifies common crime narratives
- **Clear communication:** Technical findings presented accessibly, with strong visual storytelling

---


## License

This project is for academic and demonstration purposes.  
Please contact for any commercial or public safety use.

---

*For questions or collaboration, please reach out via [LinkedIn](https://www.linkedin.com/in/carmodypaul/).*
