# Pymaceuticals Analysis 🧪  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/downloads/release/python-380/)
[![Pandas](https://img.shields.io/badge/Pandas-Library-yellow)](https://pandas.pydata.org/) 
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-red)](https://matplotlib.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)  

## Overview 📌  
This project analyzes a pharmaceutical dataset to study the effects of different drug regimens on tumor volume in mice. The analysis includes data cleaning, summary statistics, visualization, and regression modeling to draw meaningful insights.  

## Dataset 📊  
The project uses two datasets:  
- **Mouse_metadata.csv** – Contains metadata about each mouse.  
- **Study_results.csv** – Contains the results of tumor volume changes over time.  

These datasets are merged and cleaned before analysis.  

## Key Tasks 🚀  

### 🔹 Data Preparation  
- Merging **Mouse Metadata** and **Study Results** datasets.  
- Identifying and removing duplicate records.  
- Counting unique mouse IDs.  

### 🔹 Summary Statistics  
- Computing **mean, median, variance, standard deviation, and SEM** of tumor volume for each drug regimen.  

### 🔹 Visualizations  
- **Bar Charts**: Compare the number of measurements for each drug regimen.  
- **Pie Charts**: Show the distribution of male and female mice in the study.  
- **Box Plots**: Display tumor volume distribution for different drug regimens.  
- **Line Plots**: Show tumor progression for a selected mouse.  
- **Scatter Plots & Regression**: Analyze the correlation between mouse weight and average tumor volume.  

### 🔹 Correlation & Regression  
- Calculating **correlation coefficient** between mouse weight and tumor volume.  
- Performing **linear regression** to establish the relationship between these variables.  

## Results & Findings 📌  

### 📍 Tumor Volume Distribution  
![image](https://github.com/user-attachments/assets/34803b8d-a6e7-41b1-a0f3-1aaaab59bfa3)
 
The box plot highlights the tumor volume distribution for different drug regimens, with Infubinol showing a potential outlier.  

### 📍 Correlation Between Mouse Weight & Tumor Volume  
![image](https://github.com/user-attachments/assets/0f199ca9-39ea-4a42-9c26-6fb2b8dcab58)

A **strong correlation (0.88)** was found between mouse weight and tumor volume, suggesting larger mice tend to have larger tumors.  

## Installation & Dependencies 🛠  
Ensure you have the following dependencies installed:  

```bash
pip install pandas matplotlib numpy scipy
```
or install from requirements.txt:
```bash
pip install -r requirements.txt
```

## Usage ▶️
Run the Jupyter Notebook:
```bash
jupyter notebook pymaceuticals_starter.ipynb
```
## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.


## Acknowledgments

This project was developed with the assistance of the following resources:

- **"U of T" (Turtoring Session - Xpert Learning Assistant - GitLab Activites)** – Provided guidance on code and explanations.
- **ChatGPT** – Assisted with code, explanations, and README formatting. 
