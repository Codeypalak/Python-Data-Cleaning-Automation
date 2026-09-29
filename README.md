# Data Cleaning & Reporting Automation

A Python-based automation project to clean messy datasets and generate automated reports with visual summaries.

This project was built as part of **Thiranex - Task 4: Data Cleaning & Reporting Automation**.

### 🚀 Features
- **Handles Missing Values:** Filled NaN values using Mean and 'Unknown' placeholder
- **Removes Duplicates:** Automatically detects and removes duplicate records
- **Fixes Inconsistent Data:** Standardized text data using `strip()` and `title()` (e.g., `bhopal`, `DELHI`, ` palak ` -> `Bhopal`, `Delhi`, `Palak`)
- **Automated Reporting:** Generates a summary report of cleaning actions
- **Visual Summary:** Creates bar chart and histogram for cleaned data analysis

### 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

### 📂 Project Structure
- `Data_Cleaning_Automation.ipynb` - Main Jupyter notebook with full workflow
- `raw_data.csv` - Messy dataset (before cleaning)
- `cleaned_data.csv` - Cleaned dataset (after cleaning)
- `report_chart.png` - Visual summary charts

### ⚙️ Workflow
1.  **Load Messy Data:** Created a dataset with missing values, duplicates, and inconsistent formats.
2.  **Data Cleaning Automation:**
    - `df.fillna()` for missing values
    - `df.drop_duplicates()` for duplicates
    - `str.strip().str.title()` for inconsistent text
3.  **Reporting Automation:** Printed summary stats and saved a text report.
4.  **Visualization:** Automated generation of City-wise count and Salary distribution charts.

### 📊 Output
- Cleaned records: 6
- Charts generated: Employees by City & Salary Distribution

### 🔗 Author
Palak | Data Analytics Enthusiast | Thiranex Intern
