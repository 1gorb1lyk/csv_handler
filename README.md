# CSV Handler
This project demonstrates various techniques for handling CSV (Comma-Separated Values) files in Python. It covers both the built-in csv module and the pandas library, providing practical examples for different CSV operations.

## Project Structure

```
csv_handler/
│
├── .gitignore
├── change_delimiter.py
├── csv_dictreader.py
├── csv_dictwriter.py
├── employee_data.csv
├── employee_data1.csv
├── employee_data2.csv
├── employee_file.csv
├── employee_file1.csv
├── hrdata.csv
├── hrdata_modified.csv
├── pandas_reads_csv.py
├── pandas_to_csv.py
├── reading_csvfile.py
├── README.md
├── using_quotechar.py
└── writing_csv.py
```
## Features
This project covers the following CSV handling techniques:
### Using the csv module
- Reading CSV files `reading_csvfile.py`
- Writing CSV files `writing_csv.py`
- Using DictReader and DictWriter `csv_dictreader.py`, `csv_dictwriter.py`
- Changing delimiters `change_delimiter.py`
- Handling quoting `using_quotechar.py`

### Using Pandas
- Reading CSV files into DataFrames `pandas_reads_csv.py`
- Writing DataFrames to CSV files `pandas_to_csv.py`

## Usage
To run the Python scripts, use:
```
python reading_csvfile.py
```

## Sample Data
The project includes several CSV files for demonstration purposes:

- `employee_data.csv`, `employee_data1.csv`, `employee_data2.csv`: Various employee data samples
- `hrdata.csv`: Human Resources data sample
- `employee_file.csv`, `employee_file1.csv`: Output files from write operations
- `hrdata_modified.csv`: Modified HR data after pandas operations

## Requirements
- Python ^3.9
- Pandas library (for `pandas_reads_csv.py` and `pandas_to_csv.py`)

To install pandas:
```
pip install pandas
```