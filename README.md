# csv_gen

Sample Python - Circa 2019

This Python command-line utility was built to automate the conversion of multi-sheet Excel workbooks into individual files for downstream data processing.

The script reads an Excel workbook using pandas, identifies each worksheet, creates a dedicated output directory, and exports every sheet as a separate CSV or XLSX file. Output files retain the original workbook and worksheet names so the resulting datasets remain easy to identify and organize.

The utility uses Click to provide a simple command-line interface and allows the desired output format to be selected when the script is run.

The script demonstrates:

- Python-based data and file automation
- Excel processing with pandas
- Automated extraction of multiple worksheets
- CSV and XLSX generation
- Dynamic file and directory creation
- Command-line tooling using Click
- Elimination of repetitive manual spreadsheet conversion
