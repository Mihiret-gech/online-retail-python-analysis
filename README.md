#Online Retail Data Analysis with Python

Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an Online Retail dataset using Python.

The main goal is to understand retail business performance by analyzing sales transactions, customer behavior, product performance, and sales trends.

The project demonstrates practical data analysis skills, including data cleaning, data exploration, statistical analysis, and data visualization.

#Business Objectives

- Understand overall sales performance.
- Identify sales trends over time.
- Analyze customer purchasing behavior.
- Identify top-performing products.
- Compare sales performance across countries.
- Investigate cancelled orders and returned items.
- Generate actionable business insights.

#Tools and Technologies

- Python – Main programming language.
- Pandas – Data manipulation and cleaning.
- NumPy – Numerical analysis.
- Matplotlib – Data visualization.
- Jupyter Notebook – Interactive data analysis.

#Dataset Description

The dataset contains online retail transaction records.

It includes the following columns:

 Column  ---- Description 

InvoiceNo ----   Transaction invoice number 
StockCode ----   Product identification code 
Description ---- Product description 
Quantity    ---- Number of products purchased 
InvoiceDate ---- Date and time of transaction 
UnitPrice   ---- Price per product 
CustomerID  ---- Customer identification number 
Country     ---- Customer's country 


#Dataset Access and Setup

The Online Retail dataset is used for this project. The cleaned dataset is provided in compressed ZIP format in the repository to reduce file size.

Step 1: Download the Dataset

Download `online_retail_cleaned.zip` from the repository's `data/` folder.

Step 2: Extract the Dataset

1. Download the ZIP file.
2. Right-click the downloaded file.
3. Select Extract All.
4. Extract `online_retail_cleaned.csv` into your local `data/` folder.

Step 3: Run the Analysis

Install the required libraries:

pip install -r requirements.txt

Open the Jupyter Notebook and update the dataset path if necessary.

Note : The original dataset can be obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail).

#Project Workflow

1. Data Understanding
   - Imported and explored the dataset.
   - Examined dataset dimensions and data types.
   - Identified missing values and duplicates.

2. Data Cleaning
   - Handled missing values.
   - Removed duplicate records.
   - Investigated negative quantities and prices.
   - Prepared the cleaned dataset for analysis.

3. Exploratory Data Analysis
   - Sales and revenue analysis.
   - Customer behavior analysis.
   - Product performance analysis.
   - Country-based analysis.
   - Time-based sales analysis.
   - Cancellation and return analysis.

4. Data Visualization
   - Created visualizations to identify patterns, trends, and relationships.
   - Used charts to communicate findings.

5. Business Insights
   - Identified important sales patterns.
   - Examined customer and product performance.
   - Developed business recommendations.

#Repository Structure


online-retail-python-analysis/
│
├── notebooks/
│   └── online_retail_analysis.ipynb
│
├── data/
│   └── online_retail_cleaned.csv
│
├── README.md
└── requirements.txt

#Installation and Usage

1. Clone the repository


git clone https://github.com/Mihiret-gech/online-retail-python-analysis.git

2. Navigate to the project folder

cd online-retail-python-analysis

3. Install the required libraries

pip install -r requirements.txt

4. Open the Jupyter Notebook

#jupyter notebook

Open `online_retail_analysis.ipynb` to explore the analysis.

#Key Findings

This project explores retail revenue, customer purchasing behavior, product performance, geographical sales patterns, and transaction trends.

Detailed findings and business recommendations are presented in the Jupyter Notebook.

#Skills Demonstrated

- Python Programming
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation
- Statistical Analysis
- Data Visualization
- Business Problem Solving
- Analytical Thinking

#Future Improvements

- Perform deeper SQL-based business analysis.
- Develop an interactive Power BI dashboard.
- Build predictive models for sales forecasting.


#Author: Mihiret Getahun

#Project: Online Retail Python Data Analysis

#Focus: Data Analytics | Python | Business Insights
