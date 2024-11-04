# PDF Data Scraper

This project is a Python script I developed as part of my Internship at Anvi Data Solution. The goal was to extract specific data from PDF files provided by the company, which contained various voucher details. My task was to create a Python code that efficiently extracts this information and saves it into an Excel file for further analysis.

## Project Overview

The PDF files included the following details:
- Voucher Names
- Voucher Numbers
- Dates
- Particulars 
- On Account of 

Using the libraries `pdfplumber` and `PyMuPDF`, I implemented a solution that accurately parses the PDFs and structures the extracted data into a user-friendly Excel format.

## Features

- **Data Extraction**: Extracts voucher names, numbers, dates, particulars, and On Account of information from PDF documents.
- **Excel Output**: Compiles the extracted data into a single Excel file (`extracted_data.xlsx`).

## Requirements

- Python 3.6 or higher
- Required libraries:
  - `fitz` (PyMuPDF)
  - `pdfplumber`
  - `pandas`
  - `openpyxl`
    
## Installation

**Clone the repository**:
git clone https://github.com/yourusername/pdf-to-excel-scraper.git

**Navigate to the project directory**:
cd pdf-to-excel-scraper

**Install the required libraries (if not done already)**:
pip install pdfplumber pandas openpyxl pymupdf

## Usage
Place your PDF file in the project directory and rename it to data.pdf. You can modify the code to specify a different file name if needed.

## Run the script:

**Run the script**:
python pdf_to_excel.py
After the script runs, the extracted data will be saved in extracted_data.xlsx

## Acknowledgments
I would like to thank Anvi Data Solution for providing me the opportunity to work on this project and for the support throughout the development process.
