# 🏭 Manufacturing Line Productivity Analysis
This project focuses on analyzing manufacturing line productivity and production downtime. The dataset contains information about production batches, products, operators, and downtime factors recorded during the manufacturing process.

The goal of this project is to prepare raw data for analysis, build a relational data model, and identify factors affecting production efficiency.

## 🛠️ Tools
- **Python (Pandas, NumPy)** - Data Preparation & Transformation
- **SQL** - Data Modeling & Analysis
- **Power BI** - Data Visualization & Reporting

## 🐍 Python - Data Preparation
The first stage of the project focused on data cleaning and transformation.

### 🔍 Key Steps:
- Imported and reviewed data from multiple Excel worksheets
- Data quality checks, including missing values and duplicate detection
- Validated potential primary keys
- Corrected improperly imported headers in the downtime dataset
- Created production timestamps and calculated actual batch duration
- Identified and handled batches crossing midnight
- Transformed downtime data from wide format to long format using melt()
- Prepared tables for SQL analysis

### 📊 Output Tables:
- Productivity
- Downtime
- Product
- Downtime_factor

The cleaned datasets were exported as CSV files and prepared for further analysis in SQL and Power BI.

