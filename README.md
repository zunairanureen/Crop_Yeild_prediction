
# 🌾 Crop Yield Prediction Using Machine Learning

[📄 Click here to view the PDF](https://drive.google.com/file/d/15tzq8ENHPErTIXScQqKu4mf7kXsiV2DV/view?usp=drive_link)


## 📌 Overview

This project applies **machine learning techniques** to predict crop yields using environmental and agricultural variables. The goal is to provide a **data-driven decision-support tool** for sustainable agriculture, helping reduce reliance on chemical inputs by highlighting the stronger role of **climatic and biological factors**.

---

## 📊 Dataset

* **Source**: Agricultural dataset covering years **1990–2013**
* **Scope**: 100+ countries, multiple crops (e.g., wheat, rice, maize, barley)
* **Features**:

  * `average_rain_fall_mm_per_year`
  * `avg_temp` (average annual temperature)
  * `pesticides_tonnes`
  * `harvested_area`
  * `crop type` (categorical)
  * `yield (hg/ha)`

---

## 🔍 Methodology

### 1. **Exploratory Data Analysis (EDA)**

* Studied **crop yield trends** across countries and crops.
* Visualized **rainfall vs. yield**, **temperature vs. yield**, and **pesticide use vs. yield**.
* Observed strong correlations between yield and environmental factors.

### 2. **Data Preprocessing & Feature Engineering**

* Handled missing values and outliers.
* Encoded categorical features (`crop type`, `country`).
* Scaled continuous features (rainfall, temperature).
* Created interaction terms (e.g., Rainfall × Temperature).

### 3. **Model Building**

* Applied multiple algorithms:

  * Linear Regression
  * Random Forest Regressor
  * XGBoost Regressor
* Split dataset: **80% training, 20% testing**.

### 4. **Evaluation**

* Metrics used: **R², RMSE, MAE**
* Achieved **\~99% prediction accuracy** with ensemble methods.
* Visualized predicted vs. actual yields → minimal error margins.

---

## 🌱 Key Findings

* **Rainfall and temperature are stronger predictors of yield than pesticide usage.**
* Some crops (e.g., rice, maize) are **more sensitive to climatic variation**.
* Reliance on **pesticides alone is not sustainable** — climate-smart and eco-friendly strategies are essential.
* Predictive models can support **policymakers, researchers, and farmers** in designing sustainable practices.

---

## 🛠 Skills & Tools Demonstrated

* **Programming**: Python (pandas, numpy, matplotlib, seaborn, plotly)
* **Machine Learning**: scikit-learn, XGBoost, Random Forests
* **Data Analysis**: Correlation studies, trend analysis, visualization
* **Applied Biology**: Understanding crop physiology, stress factors, and sustainability implications

---

## 📂 Project Structure

```
├── data/                  # Dataset files (CSV)  
├── notebooks/             # Jupyter notebooks with full workflow  
├── README.md              # Project overview (this file)

---

## 🎯 Future Work

* Expand dataset with satellite-derived environmental indices (NDVI, soil moisture).
* Apply deep learning approaches (LSTMs for time-series prediction).
* Integrate socio-economic variables for holistic prediction models.

---

## 👩‍🔬 Author

**Zunaira Nureen**

* BSc Biochemistry & Molecular Biology, University of Gujrat

---


