# R_Data_Analyses
R_Data_Analysis – Bajaj Stock Data (2003–2020)
This notebook presents a time-series and exploratory data analysis of Bajaj stock prices from 2003 to 2020 using R programming. The analysis includes data cleaning, basic statistics, and visualizations to uncover insights from stock market trends.

🔍 Contents
📥 Data Loading:

CSV file import using readr

Structure and summary of the dataset

🧹 Data Cleaning:

Handling missing values

Removing duplicates

Date formatting and type conversions

📊 Data Analysis & Transformation:

Summary statistics with summary()

Column-wise inspection and conversion

Turnover conversion to numeric

📈 (Presumed Visualizations – based on library use):

Time-series plots using ggplot2

📦 Libraries Used (in R)
r
tidyr
readr
ggplot2
dplyr
▶️ How to Run
Make sure you have R installed (or use R in Jupyter via IRkernel).

Install necessary packages in R:

r
install.packages("tidyr")
install.packages("readr")
install.packages("ggplot2")
install.packages("dplyr")
Load the notebook in an R-supported Jupyter environment or use RStudio.

🗂️ Dataset
File used: bajaj-2003-2020.csv

Contains daily stock information (Open, High, Low, Close, Turnover)
