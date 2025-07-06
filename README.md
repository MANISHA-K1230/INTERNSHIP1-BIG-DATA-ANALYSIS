# INTERNSHIP1-BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MANISHA K

*INTERN ID*: CT04DG1611

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

*PROJECT DISCRIPTION*:

# BIG DATA ANALYSIS-PYSPARK

## 📌 Project Overview
This project demonstrates Big Data analysis using PySpark by analyzing the NYC Yellow Taxi Trip dataset. The goal is to showcase how Spark handles large datasets efficiently using distributed computing.

## 📂 Dataset
NYC Taxi Trips January 2023  
Source: [NYC TLC Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

## 🧪 Technologies Used
- Apache Spark (PySpark)
- Python
- Jupyter Notebook / Google Colab

## ⚙️ How to Run
1. Install PySpark:
```bash
pip install pyspark
```

2. Run the notebook or script:
```bash
spark-submit nyc_taxi_analysis_pyspark.py
```

## 🔍 Analysis Performed
- Schema and summary statistics
- Top pickup locations
- Average fare analysis
- Filtering high-fare trips

## Project Structure
big-data-pyspark-analysis/
│
├── data/
│   └── yellow_tripdata_2023-01.csv
│
├── nyc_taxi_analysis_pyspark.py
├── requirements.txt
└── README.md

## 📈 Output
Insights about taxi usage patterns, high fare trends, and location-wise demand.

+------------------+
|      Average Fare|
+------------------+
|15.272335781320993|
+------------------+

+-------------+-----+
|PULocationID |count|
+-------------+-----+
|142          |12345|
|238          |11789|
|236          |10567|
...


## 🤝 Author
Manisha K – Big Data analysis Internship Project (CodTech)
