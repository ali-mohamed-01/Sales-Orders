import pandas as pd

# Load the Excel file to inspect its structure and content
file_path = '/mnt/data/Dashboard-NTI-EX_1.xlsx'
excel_data = pd.ExcelFile(file_path)

# Fetch the sheet names to understand the structure of the workbook
sheet_names = excel_data.sheet_names
sheet_names
