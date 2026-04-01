# 🔥 Fire Classification System
### Classifying Fire Types Across India Using NASA MODIS Satellite Data

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![NASA MODIS](https://img.shields.io/badge/Dataset-NASA%20MODIS-yellow)

🔗 **Live App:** [fire-classification-system.streamlit.app](https://fire-classification-system.streamlit.app/)

---

## Overview

This project detects and classifies fire incidents across India — vegetation, volcanic, static land, and offshore fires — using **NASA MODIS satellite data (2021–2023)**. It covers the full ML pipeline from raw data to a deployed Streamlit web app.

Built under the **AICTE × Shell × Edunet Foundation AI/ML Virtual Internship (2025)**.

---

## Features

- Merges and preprocesses three years of MODIS fire data for India
- Handles class imbalance using **SMOTE**
- Interactive fire hotspot map built with **Folium**
- Compares Logistic Regression, Decision Tree, KNN, and Random Forest
- **Random Forest** selected as best performer — exported as `.pkl` for deployment
- Streamlit app for real-time fire type prediction from MODIS inputs

---

## ML Pipeline

```
Raw MODIS Data → EDA → Feature Engineering → Scaling + SMOTE → Model Training → Evaluation → Deployment
```

**Feature Engineering** — extracted `year`, `month`, `day_of_week`, `hour` from timestamps; outlier removal via IQR; one-hot encoding of categoricals; standard scaling of numericals.

---

## Model Comparison

| Model | Performance |
|---|---|
| Logistic Regression | Baseline |
| Decision Tree | Good |
| K-Nearest Neighbors | Average |
| **Random Forest** | ⭐ Best |

Random Forest delivered the highest accuracy, most stable predictions, and handled class imbalance best after SMOTE.

---

## Tech Stack

| Category | Tools |
|---|---|
| Data Analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn, Folium |
| ML & Preprocessing | Scikit-learn, XGBoost, Imbalanced-learn |
| Statistical Analysis | Statsmodels, SciPy |
| Deployment | Streamlit |
| Dataset | NASA MODIS (2021–2023) |

---

## Getting Started

```bash
git clone https://github.com/your-username/fire-classification-system.git
cd fire-classification-system
pip install -r requirements.txt
streamlit run app.py
```

---

## Key Insights

- Random Forest achieved the highest accuracy with balanced class predictions
- Spatial-temporal features (month, hour, day) significantly improved precision
- Seasonal fire patterns are clearly visible across Indian regions in the Folium maps

---

## Future Scope

- Real-time MODIS Fire API integration
- Model explainability with SHAP / LIME
- Cloud deployment on AWS / GCP / Hugging Face Spaces
- Dynamic geospatial dashboard for live monitoring

---

## Acknowledgements

- **AICTE, Shell & Edunet Foundation** — for the internship platform and mentorship
- **NASA MODIS** — for open-access satellite fire datasets

---

> 🌍 *Leveraging AI and satellite data for environmental sustainability — one pixel at a time.*
