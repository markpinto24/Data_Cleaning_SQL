# Data Cleaning Project Using MySQL

## 📌 Project Overview
This project focuses on cleaning and processing the **World Layoffs Dataset** (2020-2023) using **MySQL**. The dataset contains information about company layoffs from major tech firms like Airbnb, Microsoft, Google, and others. The goal of this project is to transform raw, inconsistent data into a structured and reliable format suitable for analysis.

## 🗂️ Dataset Information
- **Dataset Name:** world_layoffs (2020-2023)
- **Columns Include:**
  - `company` → Name of the company
  - `industry` → Sector in which the company operates
  - `location` → Geographic location of layoffs
  - `date` → Date of layoffs
  - `total_laid_off` → Number of employees laid off
  - `percentage_laid_off` → Percentage of workforce affected
  - `stage` → Funding stage of the company
  - `country` → Country of operation
  
## 🛠️ Data Cleaning Process
The cleaning process was performed using **MySQL**, and involved the following steps:

1. **Handling Missing Values:**
   - Removed records with excessive missing data.
   - Imputed missing values where appropriate.

2. **Data Standardization:**
   - Standardized date formats.
   - Normalized company names and industry classifications.

3. **Duplicate Removal:**
   - Identified and removed duplicate entries.

4. **Data Transformation:**
   - Created a staging table to preprocess data.
   - Converted categorical values to a consistent format.

5. **Validation Checks:**
   - Ensured that numeric fields contained only valid values.
   - Checked for inconsistencies in country and location mappings.

## 📊 Insights After Cleaning
- Standardized company names improved consistency.
- Duplicate records were reduced, improving data integrity.
- Layoffs trends are more accurately represented.

## 🤝 Contributing
Feel free to open an issue or submit a pull request if you have any suggestions or improvements!

---

