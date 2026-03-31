# 🔥 Classification of Fire Types in India Using MODIS Satellite Data (Fire Classification System)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![NASA MODIS](https://img.shields.io/badge/Dataset-NASA%20MODIS-yellow)

---

### 🧭 Developed under **AICTE × Shell × Edunet Foundation Virtual Internship Program (2025)**  
**Project Theme:** *Artificial Intelligence & Machine Learning for Environmental Monitoring*

This project focuses on **detecting and classifying fire incidents across India** — such as *vegetation, volcanic, static land, and offshore fires* — using **NASA MODIS (Moderate Resolution Imaging Spectroradiometer)** satellite data.  
The workflow covers the entire ML pipeline: **data preprocessing → model training → evaluation → deployment** using **Streamlit**.

---

## 🛰️ Overview

This repository demonstrates how satellite-based Earth observation data can be used for **fire type classification and deforestation detection**.  
By leveraging **AI and geospatial data**, this project contributes toward early detection and monitoring of environmental risks in India.

---

## 📊 Key Highlights

- ✅ Combined MODIS fire data (2021–2023) for India  
- 🧩 Performed advanced preprocessing: feature engineering, scaling, and outlier handling  
- ⚖️ Handled class imbalance using **SMOTE**  
- 🌍 Conducted **spatial visualization** of fire events with **Folium**  
- 🧠 Built multiple ML models — selected **Random Forest** as the best performer  
- 💾 Exported model & scaler for deployment  
- 🚀 Developed an interactive **Streamlit app** for real-time prediction

---

## ⚙️ Workflow Summary

### 🧩 Week 1 – Data Exploration & Visualization
- Merged multiple MODIS datasets  
- Checked missing values, duplicates, and data types  
- Performed EDA using histograms, box plots, and correlation heatmaps  
- Visualized class distribution of fire types  

### 🧠 Week 2 – Advanced Preprocessing & Spatial Analysis
- Feature engineering: extracted `year`, `month`, `day_of_week`, `hour` from timestamps  
- Outlier removal via IQR method  
- One-Hot Encoding of categorical features  
- Standard scaling of numerical features  
- SMOTE applied to balance target classes  
- Folium map created for interactive fire visualization  

### 🚀 Week 3 – Model Building & Deployment
- Trained multiple models: Logistic Regression, Decision Tree, Random Forest, KNN  
- Evaluated using Accuracy, Confusion Matrix, and Classification Report  
- **Random Forest selected as best performer**  
- Model and Scaler exported (`.pkl` files)  
- Streamlit app built for user interaction and prediction  

---

## 🤖 Model Performance

| Model | Accuracy | Key Features |
|--------|-----------|---------------|
| Logistic Regression | Moderate | Baseline linear model |
| Decision Tree | Good | Handles non-linear data |
| K-Nearest Neighbors | Average | Sensitive to scaling |
| **Random Forest** | ⭐ **Best** | Robust, accurate, balanced |

---

## 🌐 Deployment (Streamlit App)

Interactive web app built using **Streamlit** — takes user input from MODIS data and predicts fire type instantly.

### Check Out:
link : 

---

## 🧠 Technologies Used

| Category                 | Tools / Libraries                       |
| ------------------------ | --------------------------------------- |
| **Data Analysis**        | NumPy, Pandas                           |
| **Visualization**        | Matplotlib, Seaborn, Folium             |
| **ML & Preprocessing**   | Scikit-learn, XGBoost, Imbalanced-learn |
| **Statistical Analysis** | Statsmodels, SciPy                      |
| **Web App Deployment**   | Streamlit                               |
| **Dataset Source**       | NASA MODIS Satellite Data (2021–2023)   |


---

## 📈 Results & Insights

- Random Forest achieved the highest accuracy and stable predictions  
- Spatial-temporal trends revealed seasonal fire patterns across India 
- Integration of temporal + geospatial features improved model precision
- Interactive Folium maps allowed visual tracking of fire hotspots

---

## 🌱 Future Scope

- Integration with real-time MODIS Fire API feeds  
- Model explainability using SHAP or LIME 
- Deployment on cloud platforms (AWS / GCP / Hugging Face Spaces)
- Enhanced geospatial dashboards for dynamic monitoring
  
---

## 🙌 Acknowledgements

This project was completed as part of the
AICTE × Shell × Edunet Foundation Virtual Internship on Artificial Intelligence & Machine Learning (2025)

Special thanks to:

- AICTE – for providing the learning platform
- Shell & Edunet Foundation – for mentorship and technical guidance
- NASA MODIS – for open-access satellite fire datasets 

---

## 🏁 Conclusion

🌍 Leveraging AI and satellite data for environmental sustainability — one pixel at a time.

---
