## 🩺 Medical Data Visualizer

This project analyzes medical examination data to explore the relationship between cardiovascular disease ❤️, body measurements, blood test results, and lifestyle habits.
Using Python, Pandas, Matplotlib, and Seaborn, the dataset is cleaned, processed, and visualized to uncover meaningful health insights.

## 📌 Features

<img width="598" height="175" alt="image" src="https://github.com/user-attachments/assets/948e2ba7-8dcc-48ec-ae11-67df92eba52e" />

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
## 📊 Visualizations
1️⃣ Categorical Plot
Shows counts of good and bad health outcomes for patients with and without cardiovascular disease.

2️⃣ Heatmap
Displays correlations between medical variables after data cleaning.

## 🔢 Calculations Performed

### 1️⃣ Body Mass Index (BMI)

#### Formula:

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

## 🧠 Key Concepts Used

- Feature Engineering
- Data Cleaning
- Outlier Removal using Quantiles
- Correlation Matrix
- Categorical Data Visualization
- Heatmap Visualization

---

## 🚀 How to Run

```bash
python main.py
