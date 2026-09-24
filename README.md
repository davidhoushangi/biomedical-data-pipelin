# Biomedical Data Cleaning Pipeline

A Python tool for cleaning and exploring structured biomedical `CSV` data.

## What does it do?
```
├── 1. Loads a CSV file and records its original row count and missing values.
├── 2. Checks that required columns are present.
├── 3. Removes exact duplicate rows when enabled.
├── 4. Converts specified columns to numbers and flags invalid entries. 
├── 5. Converts specified missing-value codes to null values.
├── 6. Flags values outside configured valid ranges and sets them to null.
├── 7. Saves the cleaned CSV and a JSON log of every change.
├── 8. Generates a report with missingness, distribution, category, and correlation charts.
```

## Repository Structure  
```
biomedical-data-pipeline/
├── README.md
├── requirements.txt
├── main.py
├── dashboard.py # dashboard to visualize 
├── config.json
├── data/
   └── sample.csv
```

## How to run it? 
```bash
pip install -r requirements.txt
```

