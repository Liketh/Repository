# Repository

**PDF Table Extraction Scripts**
These Python scripts extract tables from PDF files and process the data to create structured dictionaries based on specific categories. They utilize the pdfplumber library for PDF extraction and pandas for data manipulation.

**Requirements**
Python 3.x
pdfplumber library (pip install pdfplumber)
pandas library (pip install pandas)

**Usage**
Ensure you have Python installed on your system.
Install the required libraries using pip.
Download the scripts and the target PDF files to the same directory.
Replace the file paths in the scripts with the paths to your PDF files.
Run the scripts.

**Scripts Overview**
pdf_table_extraction.py
This script extracts tables from a PDF file and processes the data to create structured dictionaries.
It segregates tables based on specific categories and merges tables within the same category.
Each category of tables is then converted into structured dictionaries with unique structures.
The dictionaries are printed, containing the extracted data.
pdf_table_extraction_2.py
This script also extracts tables from a PDF file and processes the data to create structured dictionaries.
It follows a similar process to segregate and merge tables based on specific categories.
Each category of tables is then converted into structured dictionaries with unique structures.
The dictionaries are printed, containing the extracted data.

**Files Included**
pdf_table_extraction.py: The main Python script.
pdf_table_extraction_2.py: Another Python script.
LOCTITE-Price-List_Effective-01.07.2022_Gokul-Traders.pdf: Sample PDF file used for extraction in pdf_table_extraction.py.
DIAMOND CHAIN NEW LIST EFFECTIVE FROM 2nd MAY 2022 (2).pdf: Sample PDF file used for extraction in pdf_table_extraction_2.py.

**Additional Notes**
Ensure the PDF files follow a similar structure for accurate extraction.
Modify the scripts as necessary to fit the structure of your PDF files.
