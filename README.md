 Titanic Survival Analysis | Data analysis project

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset using **Python, NumPy, Pandas, Matplotlib, and Seaborn**. The goal is to analyze passenger information, identify factors affecting survival, and generate meaningful business insights through data visualization and statistical analysis.

---

## Dataset

- **Dataset:** Titanic Dataset
- **Rows:** 891
- **Columns:** 12
- **Source:** Kaggle Titanic Dataset

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── Titanic.csv
├── README.md
└── images/
    ├── survival_count.png
    ├── age_distribution.png
    ├── fare_distribution.png
    ├── correlation_heatmap.png

---

## Project Workflow

### 1. Data Loading
- Load dataset
- Check dataset shape
- Display first and last records

### 2. Data Cleaning
- Handle missing values
- Remove unnecessary columns
- Check duplicate records
- Data type verification

### 3. Exploratory Data Analysis
- Survival Distribution
- Age Analysis
- Fare Analysis
- Embarkation Analysis

### 4. Feature Engineering
- Family Size
- Is Alone


### 5. Data Visualization
- Bar Charts
- Histograms
- Pie Charts
- Box Plots
- Heatmap



## Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

  

---

## Key Insights

- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers had the highest survival rate.
- Third-class passengers accounted for the largest share of passengers.
- Younger passengers generally had better survival rates.
- Ticket fare varied greatly across passenger classes.
- Most passengers boarded from Southampton.
- Higher fares were generally associated with first-class passengers.

---
