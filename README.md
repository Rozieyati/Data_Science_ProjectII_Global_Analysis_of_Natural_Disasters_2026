# 🌍 Global Analysis of Natural Disaster Impacts (2020–2025)

## 🧠 Spatiotemporal Patterns in Human and Economic Losses using EM-DAT Data

---

## 📌 Project Overview

This project presents a data-driven analysis of global natural disaster impacts between 2020 and 2025 using the EM-DAT international disaster database. The study applies **Exploratory Data Analysis (EDA)**, **statistical methods**, and **machine learning (K-Means clustering)** to understand patterns in disaster frequency, regional distribution, human impacts, and economic losses.

The main objective is to uncover hidden structures in disaster data and classify disaster events into severity-based groups for better risk understanding and decision-making.

---

## 🎯 Research Objectives

- 📊 Identify the most frequent natural disaster types (2020–2025)  
- 🌍 Analyse regional distribution of disaster events  
- 📈 Examine relationships between human impact and economic losses  
- 🤖 Apply K-Means clustering to classify disaster severity levels  
- ⏳ Investigate temporal patterns of disaster occurrence  
- 📉 Assess variability of disaster impacts across regions  

---

## 📂 Dataset

- Source: EM-DAT (Emergency Events Database)  
- Organisation: Centre for Research on the Epidemiology of Disasters (CRED)  
- Coverage: 2020–2025  
- Dataset Access (GitHub): https://tinyurl.com/46au5vy8
- Official EM-DAT Platform: https://www.emdat.be

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Missing value handling  
- Duplicate removal  
- Variable selection  
- Feature scaling (StandardScaler)

### 2. Exploratory Data Analysis (EDA)
- Disaster frequency trends  
- Regional distribution analysis  
- Heatmaps (region vs year)  
- Correlation analysis  
- Scatter plots (impact relationships)

### 3. Machine Learning
- K-Means clustering (K=3)
- Elbow method for optimal K selection  
- Silhouette Score validation (0.9579)

---

## 📊 Key Findings

- 🌊 Floods and storms are the most frequent disaster types globally  
- 🌍 Asia and the Americas show higher disaster concentrations  
- 📉 Human impact and economic losses show weak correlation  
- 🤖 Three clear disaster severity clusters were identified:
  - Low-impact disasters  
  - Moderate-impact disasters  
  - High-impact disasters  

---

## 🤖 Machine Learning Results

- Optimal Clusters: K = 3  
- Silhouette Score: **0.9579 (Excellent separation)**  
- Clustering shows strong separation between disaster severity levels  

---

## 📌 Conclusion

The study demonstrates that global disaster impacts are highly heterogeneous and cannot be explained by linear relationships alone. The integration of EDA and K-Means clustering provides deeper insights into disaster severity structures and supports improved disaster risk classification.

---

## 📚 Tools & Libraries

- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 👨‍💻 Author

**Data Science Project (2020–2025 Disaster Analysis)**  
EM-DAT Based Analytical Study  

---

## ⭐ Note

This project demonstrates a full data science pipeline:
**Data Cleaning → EDA → Statistical Analysis → Machine Learning → Insight Generation**
