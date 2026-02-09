---
title: "CYCLISTIC BIKESHARE DATA CLEANING PROJECT"
date: 2023-12-03
draft: false
#github_link: "https://github.com/gurusabarish/hugo-profile"
author: "giancarlosanfuego"
tags:
  - SQL
  - SQL Server Management Studio
  - Data Cleaning
image: /images/bikeshare.png
description: ""
toc: false
---

This project focuses on cleaning and preparing the Cyclistic Bikeshare dataset for further analysis. The dataset contains information about bike trips, including usertypes, trip details, and timestamp information

STEPS:

  1. Data Importing and Loading: Imported and loaded raw data from the provided dataset into a SQL Server database for analysis.

  2. Data Cleaning: Handling Duplicates and Missing Values if any: In this step, I addressed missing values in relevant Deleting Rows: Removed rows with a "to station name" that is marked as out of circulation due to quality control. Renaming Columns:Renamed columns for clarity and consistency in naming conventions. Creating Derived Columns: Derived new columns such as day, month, and year from timestamp data for better analysis. Seasonal Classification: Added a new column "Season" based on the start month to categorize trips into seasons (e.g., Winter, Spring).

  3. Exporting Cleaned Data: Used SQL Server tools to export the cleaned dataset to a CSV file for further analysis.

  4. Documentation: Created a readme file to document the data cleaning steps, providing transparency and reproducibility.

Link to this project in [https://github.com/AnalystGian/SQL.DataCleaningProject](https://github.com/AnalystGian/SQL.DataCleaningProject)
