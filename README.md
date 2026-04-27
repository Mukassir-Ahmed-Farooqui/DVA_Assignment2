# 📊 Data Visualization & Analysis (DVA) Assignment 2

---

## 📌 Project Description

This project presents a complete **end-to-end data analysis pipeline** built on real-world data extracted using external APIs.
The objective is to perform **data extraction, preprocessing, analysis, dimensionality reduction, and advanced visualization**, along with applying **Natural Language Processing (NLP)** techniques for deeper insights.

The project combines **Data Science + Visualization + Machine Learning concepts** to explore patterns and relationships in the dataset.

---

## 🔄 Complete Project Pipeline

### 1️⃣ Data Extraction (YouTube API)

* Collected real-time data using **YouTube Data API**
* Extracted:

  * Video titles
  * Views, likes, comments
  * Channel-related metadata
* Converted API response (JSON) into structured dataset

---

### 2️⃣ Data Preprocessing

* Handled missing and inconsistent values
* Removed duplicates
* Converted categorical data into numerical format
* Normalized and scaled numerical features
* Cleaned textual data for NLP tasks

---

### 3️⃣ Exploratory Data Analysis (EDA)

* Performed statistical summaries
* Analyzed distributions using histograms
* Studied relationships using scatter plots
* Generated correlation heatmaps

---

### 4️⃣ Feature Engineering

* Created derived features such as:

  * Engagement ratio (likes/views)
  * Comment density
* Selected relevant features for modeling

---

### 5️⃣ Natural Language Processing (NLP - BERT)

* Applied **BERT (Bidirectional Encoder Representations from Transformers)**
* Converted textual data (titles/comments) into embeddings
* Captured semantic meaning of text
* Enabled deeper analysis beyond basic keyword methods

---

### 6️⃣ Dimensionality Reduction (t-SNE)

* Used **t-SNE (t-distributed Stochastic Neighbor Embedding)**
* Reduced high-dimensional data (BERT embeddings) into 2D space
* Visualized clusters and hidden structures
* Helped interpret complex relationships in data

---

### 7️⃣ Data Visualization

* Used **Matplotlib & Seaborn**
* Generated:

  * Bar charts
  * Scatter plots
  * Heatmaps
  * Cluster visualizations (t-SNE plots)
* Represented patterns clearly and effectively

---

### 8️⃣ Insights & Interpretation

* Identified patterns in user engagement
* Observed clustering of similar content
* Understood relationships between features
* Derived meaningful conclusions from visual analysis

---

## 🧠 Concepts Covered

* API-based Data Collection (YouTube API)
* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Natural Language Processing (BERT)
* Text Embeddings
* Dimensionality Reduction (t-SNE)
* Data Visualization Techniques
* Insight Generation

---

## 🛠️ Technologies Used

* **Python** 🐍
* **Jupyter Notebook** 📓
* **Pandas**
* **NumPy**
* **Matplotlib & Seaborn**
* **Scikit-learn (t-SNE)**
* **Transformers / BERT (NLP)**
* **YouTube Data API**

---

## 📂 Repository Structure

```bash
DVA_Assignment_2.ipynb   # Main implementation notebook
README.md                # Project documentation
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/repo-name.git
```

2. Navigate to the project folder:

```bash
cd repo-name
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers jupyter
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 📊 Key Features

* ✔ Real-world data extraction using API
* ✔ Advanced NLP using BERT
* ✔ High-dimensional data visualization using t-SNE
* ✔ Clean and structured pipeline
* ✔ Insightful and meaningful visualizations

---

## 📈 Results & Insights

* Discovered patterns in audience engagement
* Identified clusters of similar content using t-SNE
* Extracted semantic meaning from text using BERT
* Derived actionable insights from data

---

## 👨‍🏫 Guide

* **Panigrahi Srikanth (Assistant Professor)**

---

## 🤝 Contributors

* **Mukassir Ahmed Farooqui** (160123729305)
* **Kotla Geethika** (160123729304)
* **Panigrahi Srikanth**

---

## 🔮 Future Improvements

* Use advanced NLP models (GPT-based / fine-tuned BERT)
* Build interactive dashboards (Plotly / Streamlit)
* Apply clustering algorithms (K-Means, DBSCAN)
* Expand dataset for deeper analysis

---

## 📜 License

This project is for academic purposes only.

---

## ⭐ Acknowledgment

We sincerely thank our guide **Panigrahi Srikanth Sir** for his valuable guidance and support throughout this project.

---
