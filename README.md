

# Watershed Prioritization using ANN-based Multicriteria Decision Analysis

## 📌 Overview

This project demonstrates **watershed prioritization** using **Artificial Neural Networks (ANN)** with **Multicriteria Decision Analysis (MCDA)** on **synthetic data**. The approach integrates terrain, hydrology, soil, and land use parameters to rank watersheds for management.

## 📊 Methodology

1. **Synthetic Data Generation** – Created datasets representing slope, drainage density, soil type, land use, and rainfall.
2. **Multicriteria Decision Analysis (MCDA)** – Assigned weights to parameters based on importance.
3. **ANN Model Training** – Used weighted features to train an ANN for prioritization scores.
4. **Ranking** – Classified watersheds into **high, medium, and low priority**.

## 📂 Dataset

* Synthetic CSV file: `watershed_data.csv`
* Columns:

  * `Slope (%)`
  * `Drainage Density`
  * `Soil Permeability`
  * `Land Use Intensity`
  * `Rainfall (mm)`
  * `Priority Score` (Target)

## 🛠️ Requirements

Install dependencies before running:

```bash
pip install pandas numpy scikit-learn tensorflow matplotlib
```

## 🚀 How to Run

```bash
python watershed_prioritization.py
```

## 📈 Expected Output

* **Model performance metrics** (accuracy, loss curve)
* **Watershed priority map** (synthetic visualization)
* **Excel file** with ranked priorities

## 📜 License

This project is for educational and research purposes using synthetic data.


