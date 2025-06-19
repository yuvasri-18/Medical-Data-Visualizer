# 🩺 Medical Data Visualizer

This project analyzes and visualizes patient data from medical examinations using Python, Pandas, Seaborn, and Matplotlib.

## 📊 Features

- Calculates BMI and flags patients as overweight
- Normalizes cholesterol and glucose levels
- Creates a categorical plot comparing lifestyle/health factors with/without cardiovascular disease
- Generates a heatmap showing feature correlations after cleaning the data

## 📁 Dataset

File: `medical_examination.csv`

Columns include:
- Objective: `age`, `height`, `weight`, `gender`
- Examination: `ap_hi`, `ap_lo`, `cholesterol`, `gluc`
- Lifestyle: `smoke`, `alco`, `active`
- Target: `cardio` (1 = disease, 0 = healthy)

## 🧪 How to Use

1. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib numpy
   
🧠 Libraries Used

Python 3

Pandas

Seaborn

Matplotlib

NumPy
