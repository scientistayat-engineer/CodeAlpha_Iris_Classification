# **CodeAlpha_Iris_Classification**

### Advanced Machine Learning pipeline built to classify Iris flower species using multi-paradigm benchmarking models for the CodeAlpha Internship.

# **🌸 Iris Flower Species Classification**

**Production-Grade Machine Learning Pipeline | CodeAlpha Data Science Internship — Task 1**

---

## **📋 Executive Project Summary**

#### This repository houses a comprehensive, end-to-end Data Science workflow constructed to evaluate and classify Iris flower species (*Setosa*, *Versicolor*, and *Virginica*) using structural continuous botanical metrics. 

#### The pipeline benchmarks multiple machine learning paradigms—ranging from linear models to ensemble frameworks and instance-based spatial algorithms—and deploys a custom, dynamic real-time live inference engine.

---

## **📊 Analytical Insights & Core Findings**

* **Perfect Target Separation:** Structural analysis through pairplots confirms that **Iris-setosa** forms a completely isolated cluster, making it linearly separable based solely on Petal properties.
* 
* **Dominant Feature Weights:** Pearson correlation mapping indicates that **Petal Length** and **Petal Width** hold an exceptionally high dependency ratio ($r = 0.96$), acting as the strongest algorithmic discriminators.
* 
* **Model Dominance:** **K-Nearest Neighbors (KNN)** achieved a perfect **100.00% validation accuracy**, capitalizing on the dataset's clear spatial clustering. **Logistic Regression** tracked closely behind at **96.67%**, with only a single marginal boundary overlap.

---

## **🛠️ Technology Stack & Engine Specs**

* **Environment:** Jupyter Notebook inside VS Code (Python 3.12)

* **Core Analytics Suites:** `Pandas`, `NumPy`

* **Data Visualization Frameworks:** `Matplotlib`, `Seaborn`

* **Statistical Machine Learning Engine:** `Scikit-Learn`

---

## **📐 End-to-End Pipeline Architecture**

### **Phase 1: Ingestion & Structural Quality Audit**

* Systematic streaming of tabular raw files into structural Pandas DataFrames.
  
* Automated verification of data types, dimensional metrics, and verification of zero missing or null records.

### **Phase 2: Advanced Exploratory Data Analysis (EDA)**

* Multi-dimensional pairplots mapping target separations.
  
* Annotated Pearson heatmaps exposing feature correlation vectors.
  
* Stratified distribution boxplots to map variations and audit spatial anomalies.

---

### **Phase 3: Matrix Extraction & Stratified Splitting**

* Feature-target matrix separation.
  
* Implemented **Stratified Sampling** (`stratify=y`) with a balanced 80/20 train-test split, maintaining exact class distribution ratios ($1:1:1$) across data splits to secure predictive integrity.

---

### **Phase 4: Production-Grade Inference Engine (Live Testing)**
* Integrated an independent, dynamic testing system. The engine is engineered to accept runtime multi-variate continuous inputs and instantly compute simultaneous class predictions across all trained frameworks.

---
**Developed with 💻 by Ayat Adnan | Data Science Intern at CodeAlpha (2026)**
