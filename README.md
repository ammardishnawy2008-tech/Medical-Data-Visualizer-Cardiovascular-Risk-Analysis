# Medical-Data-Visualizer-Cardiovascular-Risk-Analysis
A data analysis and visualization project that explores medical examination data to identify relationships between cardiovascular disease, body measurements, blood markers, and lifestyle habits using Python, Pandas, and Seaborn.
# Medical Data Visualizer 🩺📊

## Project Overview
This project analyzes and visualizes medical examination data to explore relationships between cardiovascular disease, body measurements, blood test results, and lifestyle choices.  
The goal is to extract meaningful insights using data cleaning, transformation, and visualization techniques in Python.

This project is part of the **freeCodeCamp Data Analysis with Python** curriculum.

---

## Dataset Description
The dataset contains medical examination records where:
- Each row represents a patient
- Each column represents a medical or lifestyle attribute

### Features
| Column | Description |
|------|------------|
| age | Age in days |
| gender | Gender (categorical) |
| height | Height in cm |
| weight | Weight in kg |
| ap_hi | Systolic blood pressure |
| ap_lo | Diastolic blood pressure |
| cholesterol | Cholesterol level (normalized) |
| gluc | Glucose level (normalized) |
| smoke | Smoking status |
| alco | Alcohol intake |
| active | Physical activity |
| overweight | Overweight indicator (BMI > 25) |
| cardio | Presence of cardiovascular disease |

---

## Tools & Libraries
- **Python**
- **Pandas** – data cleaning and manipulation
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations
- **NumPy** – numerical operations

---

## Data Processing Steps
1. Loaded and explored the medical dataset.
2. Calculated BMI and created the `overweight` feature.
3. Normalized cholesterol and glucose values:
   - `0` → normal (good)
   - `1` → above normal (bad)
4. Removed incorrect and extreme data points.
5. Prepared data for visualization and correlation analysis.

---

## Visualizations
### 1. Categorical Plot
- Shows the distribution of lifestyle and medical risk factors.
- Compares patients **with** and **without** cardiovascular disease.

### 2. Correlation Heatmap
- Displays relationships between medical measurements and lifestyle factors.
- Highlights strong correlations such as:
  - Blood pressure & cardiovascular disease
  - Weight & systolic pressure
  - Glucose & cholesterol

---

## Key Insights
- Cardiovascular disease increases with **age**.
- **High blood pressure** is strongly associated with heart disease.
- **Overweight patients** show higher cardiovascular risk.
- **Low physical activity**, combined with metabolic risk factors, contributes to disease prevalence.
- Medical and lifestyle factors are deeply interconnected rather than independent.

---

## Project Structure
