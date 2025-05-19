# solar-challenge-week1

## Setup Instructions

To reproduce the environment:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/solar-challenge-week1.git
   cd solar-challenge-week1

2. Exploratory Data Analysis

Overview This Python script provides a menu-driven interface for analyzing datasets related to solar radiation, wind conditions, and temperature data.

Dataset Selection The script expects the datasets in CSV format. You can configure dataset paths in the datasets dictionary at the beginning of the script: 
   • benin-malanville.csv 
   • sierraleone-bumbuna.csv
   • togo-dapaong_qc.csv

Analysis Options 

   • Summary Statistics 
   • Data Quality Check 
   • Time Series Analysis 
   • Correlation Analysis 
   • Wind Analysis 
   • Temperature Analysis 
   • Histograms 
   • Z-Score Analysis 
   • Bubble Charts 
   • Data Cleaning

Requirements To run this script, the following libraries must be installed: 

   • pandas 
   • matplotlib 
   • seaborn 
   • numpy 
   • windrose

Install them using:

pip install pandas matplotlib seaborn numpy windrose

Launch Jupyter Notebook

jupyter notebook
notebooks/benin_eda.ipynb

Run All Cells

Click "Cell" > "Run All"

Or run sections one by one using Shift + Enter

License This project is licensed under the MIT License.