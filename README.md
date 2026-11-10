Nathaniel Lo Tzin Ye
 B.Eng. Computer Engineering, Nanyang Technological University (NTU), Singapore

I build end-to-end data and ML systems: from raw data ingestion and big-data pipelines to deep learning models that are evaluated, documented and reproducible. My final-year project on 3D dental AI is published in the NTU Digital Repository.

- 🔭 Applied deep learning, 3D / geometric Machine Learning, Data Engineering, Data Analytics
- 🌱 I am looking for **Data Scientist / ML Engineer / Data Engineer** roles in Singapore
- 📫 Reach me: [LinkedIn](https://www.linkedin.com/in/lotzinyenathaniel/) · [Email](mailto:lotzinye@gmail.com)

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/ESM_%2F_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data Engineering**

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop_HDFS-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![Hive](https://img.shields.io/badge/Apache_Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apache&logoColor=white)

**Analysis & Visualisation**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_%2F_WSL-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🚀 Featured Projects

### 🦷 [Automated 3D Tooth Segmentation & Landmark Detection](https://github.com/lotzinye/3D-Dental-Segmentation-Landmark-Detection-Deep-Learning-Pipeline)
*Final Year Project · NTU · [Publication](https://dr.ntu.edu.sg/entities/publication/9c514406-141c-4615-8594-8c4bc19be852)*

End-to-end deep learning pipeline that takes a raw intraoral jaw scan (`.obj`) and outputs a per-vertex FDI tooth label plus 3D coordinates for six anatomical landmark classes on every tooth — no manual input.

- **Segmentation:** TSA **0.984**, TLA **0.949**, 3DTeethSeg'22 challenge score **0.804** on 240 held-out scans
- **Landmark detection:** mAP **0.622** / mAR **0.483** across 6 classes (MICCAI 2024 protocol)
- Designed a **coordinate-space bridge** that lets two networks trained under different normalisations work as one system
- Solved variable-count cusp detection with a dedicated output head + DBSCAN clustering

`PyTorch` `3D point clouds` `Medical imaging` `DBSCAN`

---

### 🚇 [Singapore MRT Ridership Big-Data Pipeline](https://github.com/lotzinye/LTA-MRT-Rideship-Big-Data-Pipeline)

Big-data pipeline on **3.5M+ origin–destination trip records** from LTA DataMall: ingest → HDFS → PySpark cleaning/enrichment → Hive tables → Spark SQL analytics → MLlib clustering, all containerised with Docker Compose.

- Found the busiest weekday corridor (**Tampines → Pasir Ris, 495K trips**) and bimodal weekday peaks (6pm: 28.1M trips)
- Clustered 182 stations with K-Means (k=4, **silhouette 0.576**) into feeder, commuter-hub and CBD groups
- Reached **100% station-name coverage** by resolving interchange codes and geocoding with WikiData + OneMap

`PySpark` `Hadoop HDFS` `Hive` `Spark MLlib` `Docker`

---

### 🧬 [Protein Secondary Structure Prediction](https://github.com/lotzinye/Protein-Secondary-Structure-Prediction-PSSP-SC4001-Project)
*Team project · SC4001 Neural Networks & Deep Learning*

Predicts protein secondary structure (Q3 / Q8) from amino-acid sequence alone. Iterated from Transformer and CNN-BiLSTM baselines to a final hybrid **Transformer + dilated CNN** using **ESM protein-language-model embeddings**.

- Final model: Q3 macro-F1 **0.871** (up from 0.704 baseline) · Q8 macro-F1 **0.521**
- Built CLI training tooling with AMP, OneCycleLR, label smoothing and macro-F1 checkpointing

`PyTorch` `Transformers` `ESM` `Bioinformatics`

---

### 📈 [OCBC Stock Price Tracking & Prediction](https://github.com/lotzinye/OCBC-Market-Price-Tracking-Visualisation)

Exploratory analysis of OCBC (O39.SI) market data via `yfinance`: interactive candlestick charts with moving averages and Bollinger Bands, plus a scikit-learn classifier for next-day price direction.

`pandas` `Plotly` `scikit-learn` `Time series`

---
