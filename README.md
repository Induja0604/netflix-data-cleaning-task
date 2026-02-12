# netflix-data-cleaning-task
Data cleaning and preprocessing of Netflix dataset using Python (Pandas)
##  Objective
The objective of this task is to clean and preprocess the Netflix dataset using Python and Pandas.

---

##  Steps Performed

### 1️⃣ Handling Missing Values
- Identified missing values using `df.isnull().sum()`
- Removed unnecessary columns
- Filled missing values where required

### 2️⃣ Removing Duplicates
- Checked duplicates using `df.duplicated()`
- Removed duplicates using `df.drop_duplicates()`

### 3️⃣ Standardizing Text Data
- Converted text columns to lowercase
- Removed extra spaces
- Standardized country names

### 4️⃣ Date Formatting
- Converted `date_added` to datetime using `pd.to_datetime()`
- Formatted date into consistent structure

### 5️⃣ Data Type Conversion
- Converted `release_year` and `duration` to numeric
- Converted categorical columns to category type

---

##  Files Included
- `Netflix_Raw_Dataset.csv` – Raw dataset
- `netflix_data_cleaning.ipynb` – Python notebook with complete code

---

## Tools Used
- Python
- Pandas
- Jupyter Notebook

---

## Outcome
The dataset was cleaned and prepared for further analysis and visualization.

Developed by: Induja
