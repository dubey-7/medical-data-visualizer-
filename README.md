# 🏥 Medical Data Visualizer

## 📌 Project Overview

This project analyzes medical examination data to explore the relationship between:

- Cardiovascular disease
- Body measurements
- Blood markers
- Lifestyle habits

The dataset was collected from real medical examinations.

---

## 📊 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

---

## 📁 Dataset

File used: `medical_examination.csv`

Each row represents a patient and columns include:

- age
- height
- weight
- cholesterol
- gluc
- smoke
- alco
- active
- cardio

---

# 🔢 Calculations Performed

## 1️⃣ Body Mass Index (BMI)

### Formula:

\[
BMI = \frac{Weight (kg)}{Height (m)^2}
\]

If:

- BMI > 25 → Overweight (1)
- BMI ≤ 25 → Not Overweight (0)

---

## 2️⃣ Data Normalization

For better analysis:

- cholesterol:
  - 1 → 0 (Normal / Good)
  - >1 → 1 (High / Bad)

- gluc:
  - 1 → 0 (Normal / Good)
  - >1 → 1 (High / Bad)

---

# 📈 Visualizations

## 1️⃣ Categorical Plot

Shows count of:

- cholesterol
- gluc
- smoke
- alco
- active
- overweight

Separated by:

- cardio = 0 (No heart disease)
- cardio = 1 (Heart disease)

Purpose:
To analyze lifestyle & medical risk factors in heart disease patients.

---

## 2️⃣ Heatmap

Steps performed:

- Removed incorrect blood pressure values  
  (diastolic ≤ systolic)
- Removed extreme outliers (2.5% - 97.5%)
- Calculated correlation matrix
- Displayed lower triangular heatmap

Purpose:
To identify relationships between medical variables.

---

# 🧠 Key Concepts Used

- Feature Engineering
- Data Cleaning
- Outlier Removal using Quantiles
- Correlation Matrix
- Categorical Data Visualization
- Heatmap Visualization

---

# 🚀 How to Run

```bash
python main.py
