# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PRISCILLA M

*INTERN ID*: CT04DN1650

*DOMAIN*: DATA ANALYSIS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

**Big Data Analysis: Indian Accident Analysis**

All steps from data loading to deriving insights, were executed using PySpark on Google Colab with proper Spark setup and configuration.

*Tools Used*: Google Colab + PySpark, pyspark.sql for querying and aggregations, Spark functions for date/time parsing, grouping, and filtering

Environment Setup
1. Installed OpenJDK 8, downloaded and extracted Apache Spark, and configured environment variables.

Installed PySpark and Findspark to link Jupyter/Colab with Spark runtime.

2. Data Loading and Schema Inspection
   
Loaded the dataset using spark.read.csv(), inferred the schema, and explored initial rows.

3. Data Cleaning
   
Counted total rows and null values in each column using isNull() and when() functions.

Since there were no significant missing values, no data was dropped or imputed.

4. Exploratory Data Analysis (EDA)
   
Using PySpark's SQL-like operations:

State-wise accident count: Top 3 states were Tripura (TR), Delhi (DL), and Gujarat (GJ).

Weather-wise analysis: Foggy weather had the most accidents.

Severity distribution: Fatal, Serious, and Slight accidents were almost evenly distributed.

Vehicle type: Motorcycles and trucks were involved in most accidents.

Monthly trends: March and October had the highest accident counts.

Year-wise comparison: 2023 showed slightly fewer accidents than 2022.

5. Time-based Analysis
   
Converted date column using to_date() and extracted year and month.

Grouped accidents by month and year to visualize trends.

*KEY INSIGHTS*

Fog was the weather condition during most severe accidents.

Accidents were consistently high in March and October across years.

Tripura, Delhi, and Gujarat recorded the highest number of accidents in this dataset.

Motorcycles were the most common vehicle involved in accidents.

Severity distribution indicates a balanced risk across all three levels (Fatal, Serious, Slight).




