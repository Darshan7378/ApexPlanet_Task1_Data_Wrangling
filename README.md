# ApexPlanet Data Analytics Internship
## Task 1: Data Immersion and Wrangling

### Project Overview
This project focuses on understanding, assessing,
cleaning and transforming a sales dataset using
Python and Pandas.

The objective is to identify data quality issues
and prepare a clean dataset for further analysis.

### Dataset Information
- Dataset Name: ApexPlanet_DataAnalytics_Dataset
- Original File Format: Excel
- Total Records: 1,000
- Total Columns: 12
- Domain: Sales Analytics

### Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- GitHub

### Tasks Performed

1. Data Loading
   - Loaded the Excel dataset using Pandas.
   - Inspected rows, columns and data types.

2. Data Dictionary
   - Documented all 12 columns.
   - Explained variable meanings and business relevance.

3. Data Quality Assessment
   - Checked missing values.
   - Checked duplicate records.
   - Identified repeated Order_ID values.
   - Checked inconsistent formatting.
   - Detected outliers using the IQR method.
   - Verified sales calculations.

4. Data Cleaning
   - Filled missing Age values using the median.
   - Filled missing City values using the mode.
   - Converted Order_Date into datetime format.
   - Removed unnecessary spaces.
   - Standardized categorical text formatting.
   - Retained potentially valid high-value transactions.
   - Removed temporary verification columns.

### Data Quality Findings
- 20 missing values in Age.
- 13 missing values in City.
- 0 exact duplicate rows.
- 9 records associated with repeated Order_ID ORD100050.
- 19 outliers identified in Total_Sales.
- 0 incorrect sales calculations.

### Final Dataset
The cleaned dataset contains:
- 1,000 rows
- 12 columns
- 0 missing values
- 0 exact duplicate rows

The repeated Order_ID issue was documented
without deleting the associated transactions.
The 19 high-value sales records were retained
after checking their calculations.

### Project Files
- ApexPlanet_Cleaned_Dataset.csv
- data_dictionary.md
- data_cleaning.ipynb
- README.md

### Conclusion
The sales dataset was successfully assessed
and cleaned using Python and Pandas.
The final dataset is ready for further
data analysis and visualization.

### Internship
ApexPlanet Data Analytics Internship
Task 1 – Data Immersion and Wrangling
