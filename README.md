# 💧 Water Quality Prediction

This project focuses on analyzing and predicting water quality using chemical parameter data such as ammonium, nitrate, phosphate, dissolved oxygen, and more.

## ✅ Current Progress (Week 1)

- Loaded and cleaned the dataset (`.csv`) with semicolon (`;`) delimiter.
- Converted date column to proper `datetime` format.
- Performed exploratory data analysis (EDA), including:
  - Histograms and boxplots to understand distribution and outliers
  - Time-series trends for selected pollutants
  - Correlation heatmap to study relationships between chemical indicators


## 🔬 Dataset Features

| Column     | Description                        |
|------------|------------------------------------|
| `id`       | Sampling location ID               |
| `date`     | Date of measurement                |
| `NH4`      | Ammonium (mg/L)                    |
| `BSK5`     | BOD5 - Biochemical oxygen demand   |
| `Suspended`| Suspended solids (mg/L)            |
| `O2`       | Dissolved oxygen (mg/L)            |
| `NO3`      | Nitrate (mg/L)                     |
| `NO2`      | Nitrite (mg/L)                     |
| `SO4`      | Sulfate (mg/L)                     |
| `PO4`      | Phosphate (mg/L)                   |
| `CL`       | Chloride (mg/L)                    |
