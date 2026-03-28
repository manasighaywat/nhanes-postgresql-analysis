# NHANES Body Measurement Analysis using PostgreSQL

## 📌 Project Overview
Analysis of 8302 adult body measurements from NHANES 2020 dataset 
using Python and PostgreSQL.

## 🛠️ Tools & Technologies
- Python (Pandas, Matplotlib, Seaborn)
- PostgreSQL
- SQLAlchemy & psycopg2
- Jupyter Notebook

## 📊 Analysis Performed
- Average weight, height and BMI by gender
- BMI category distribution (Underweight, Normal, Overweight, Obese)
- Window Functions - BMI ranking within gender
- Subquery - People with BMI above average
- Waist to Hip and Waist to Height ratio analysis
- Correlation between all body measurements

## 📈 Key Findings
- Average Female BMI: 30.10 (Obese category)
- Average Male BMI: 29.14 (Overweight category)
- 1938 Females and 1651 Males have BMI above average
- Males have higher average waist (101.79 cm) than females (98.49 cm)
- Females have higher average hip (109.18 cm) than males (104.50 cm)

## 📂 Files
- `nhanes_postgresql.ipynb` - Main analysis notebook
- `nhanes_analysis.png` - Basic analysis charts
- `nhanes_advanced_analysis.png` - Advanced analysis charts
