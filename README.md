# Data Import and Processing with Pandas

## Overview

This project demonstrates how to use the **Pandas** library to read data from multiple sources, clean missing values, and save the processed data. It imports data from a CSV file, an Excel file, and an online dataset, performs basic preprocessing, and exports the cleaned datasets.

---

## Features

- Read data from a CSV file
- Read data from an Excel file
- Read data from a web URL
- Display the first five rows of each dataset
- Handle missing values using forward fill and backward fill
- Remove missing values from web data
- Save processed data to new CSV and Excel files

---

## Technologies Used

- Python 3.x
- Pandas

---

## Prerequisites

- Python 3.8 or later
- Pandas library
- OpenPyXL (for Excel support)

---

## Installation

Install the required libraries:

```bash
pip install pandas openpyxl
```

---

## Dataset

Place the following files in your **Downloads** folder:

- `sample_billing.csv`
- `sample_billing.xlsx`

The program also downloads a sample dataset from:

```
https://raw.githubusercontent.com/cs109/2014_data/master/countries.csv
```

---

## How to Run

Run the Python script:

```bash
python data_import_processing.py
```

Or execute the code in a Jupyter Notebook.

---

## Operations Performed

### Data Import
- Read CSV file using `pd.read_csv()`
- Read Excel file using `pd.read_excel()`
- Read an online CSV dataset from a URL

### Data Preview
- Display the first five rows of each dataset using `head()`

### Data Cleaning
- Apply forward fill (`ffill()`) to the CSV dataset
- Apply backward fill (`bfill()`) to the Excel dataset
- Remove rows with missing values from the web dataset

### Data Export
- Save the processed CSV dataset as `processed_text.csv`
- Save the processed Excel dataset as `processed_excel.xlsx`

---

## Output Files

After execution, the following files are created:

- `processed_text.csv`
- `processed_excel.xlsx`

The console also displays the first five rows of all three datasets and prints:

```text
Files processed successfully!
```

---

## Project Structure

```
data-import-processing/
├── data_import_processing.py
├── sample_billing.csv
├── sample_billing.xlsx
├── processed_text.csv
├── processed_excel.xlsx
├── requirements.txt
└── README.md
```

---

## Requirements

Create a `requirements.txt` file with:

```text
pandas
openpyxl
```

---

## Learning Outcomes

After completing this project, you will be able to:

- Import data from CSV, Excel, and web sources.
- Handle missing values using different techniques.
- Export cleaned datasets.
- Perform basic data preprocessing using Pandas.

---

## Author

**Anushri A**

B.E. Computer Science and Engineering

Chennai Institute of Technology

---

## License

This project is intended for educational and learning purposes.
