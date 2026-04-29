# mineral-prospectivity-ml
AI-based mineral prospectivity mapping using ML Keep it Public

# 🧠 AI-Based Mineral Prospectivity Mapping

### Predicting Gold Occurrence using Machine Learning & Geospatial Analysis

---

## 📌 Overview

The mining industry is often described as *“data-rich but information-poor”*. This project addresses that challenge by developing a machine learning-based system to **predict the probability of gold occurrence** using geological and spatial features.

The model integrates multiple factors such as rock type, proximity to geological fault lines, and magnetic intensity to generate **data-driven exploration insights**.

---

## 🎯 Objective

* Build a predictive model for **mineral (gold) prospectivity mapping**
* Demonstrate how AI can assist in **resource exploration and decision-making**
* Visualize predictions using **interactive geospatial maps**

---

## 🧩 Methodology

### 1. Data Simulation

Due to limited public availability of real mining datasets, a synthetic dataset was generated to mimic real-world geological patterns, including:

* Latitude & Longitude
* Rock Type (encoded categories)
* Distance to Fault Lines
* Magnetic Intensity

Target variable:

* `Gold Presence` (1 = likely, 0 = unlikely)

---

### 2. Machine Learning Model

* Algorithm: **Random Forest Classifier**
* Reason: Robust performance on tabular + nonlinear data

Steps:

* Data preprocessing
* Train-test split
* Model training
* Performance evaluation

---

### 3. Model Interpretation

To enhance transparency and interpretability:

* **Feature Importance Analysis**
* **SHAP (SHapley Additive exPlanations)** used to understand feature contributions

---

### 4. Geospatial Visualization

An interactive map was created using **Folium** to display predictions:

* 🔴 Red points → High probability of gold occurrence
* 🔵 Blue points → Low probability

This transforms raw predictions into **intuitive spatial insights**.

---

## 📊 Results

* Achieved strong classification performance on simulated data
* Identified key influencing factors:

  * Rock Type
  * Distance to Fault Lines
  * Magnetic Intensity

The model successfully demonstrates how AI can be applied to **mineral exploration targeting systems**.

---

## 🛠️ Tech Stack

* **Programming:** Python
* **Libraries:**

  * Pandas, NumPy
  * Scikit-learn
  * Matplotlib, Seaborn
  * Folium
  * SHAP

---

## 🌍 Applications

This project aligns with modern AI applications in mining, including:

* Mineral exploration targeting
* Resource estimation
* Environmental and ESG analytics
* Decision support systems for mining operations

---

## 🚀 Future Improvements

* Use real-world geological & satellite datasets
* Integrate **hyperspectral imaging data**
* Apply **deep learning models (CNNs)** for spatial analysis
* Deploy as a **web application (Streamlit)**

---

## 📷 Project Visuals
* Gold Presence
<img width="371" height="274" alt="image" src="https://github.com/user-attachments/assets/67d6e9ba-3905-4a67-9898-107a6eb84bde" />


* Prediction Map
<img width="458" height="335" alt="image" src="https://github.com/user-attachments/assets/c3c886e3-3949-4d53-ae38-84574e987dc8" />

* SHAP Feature Importance Plot
<img width="185" height="256" alt="image" src="https://github.com/user-attachments/assets/d3dab181-09a1-4408-bc1b-af6cc6e2ba86" />

---

## 📚 Conclusion

This project demonstrates how machine learning can transform traditional geological workflows by converting raw data into **actionable exploration insights**. It highlights the potential of AI in building **smarter, safer, and more efficient mining systems**.

---

## 👤 Author

**[POOJA]**

* Aspiring AI/ML Engineer
* Interested in AI applications in real-world systems

---
