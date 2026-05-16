## **Medical Insurance Charges** 

## Overview  
This data contains clean and structured insurance data including demographic information, risk factor, smoking status,insurance tier, and insurance charges. The primary objective of this project is to analyze the factors that influence health insurance consts and understand how variables such as age, BMI, and smoking habits contrubute to overall insurance charges. 
 
## Repository Contents
- medical_insurance_2026_kaggle.csv - dataset containing multiple years of insurance charges based on age, insurance tier, and risk factor. 
- Insurance_cost_analysis.ipynb - Jupyter Notebook 
- README.md

## Project Objectives
- Analyze the relationship between insurance charges and demographic factor  
- Identify major contributor to higher insurance costs
- Visulizations

## Analysis and Visulization     
  - Data cleaing and wrangling    
  - Exploratory Data Analaysis (EDA)  
  - Distribution of gender and insurance charges by gender (pie chart and bar plot)
  - Age distribution and impact of age on insurance charges (histogram and scatter plot)
  - Smoking status impact on insurance charges (scatter plot)
  - Correlation analysis (Head Map)

## Instructions
1. #### Fork and Clone the Repository
```bash
   git clone https://github.com/bebinshrestha/Insurance_Cost_Analysis.git
```
2. #### Open the Notebook
   Open 'Insurance_cost_analysis.ipynb' in Jupyter Notebook
## Usages
```bash
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
```
```bash
df = pd.read_csv("data/medical_insurance_2026_kaggle.csv")
df.head()
```

## Author
Bebin Shrestha - Code:You Student

## License
Open source under the Creative Commons which states that "you can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission." 