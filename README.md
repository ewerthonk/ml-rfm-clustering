> **Note:** This project is currently in progress.

# Retail Ecommerce RFM Clustering 

<div align="center">
  <em>Running an RFM analysis and clustering on retail ecommerce data.</em>
</div>

<br>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
</div>

## 📖 Project

### 👨🏻‍🏫 Introduction

This project focuses on implementing a **customer segmentation model** for an e-commerce retail company, leveraging the **RFM (Recency, Frequency, Monetary)** methodology and **K-Means clustering**. The goal is to identify customer behavior patterns and enable data-driven marketing strategies that maximize engagement and revenue.

### 🎯 Goals

- Exploratory Data Analysis: explore and reveal initial insisghts about the data.
- RFM Segmentation: Calculate recency, frequency, and monetary values for customer ranking.
- Clustering: Apply K-Means to group customers based on their purchasing behavior.
- Insights: Provide actionable insights to optimize marketing strategies for each customer segment.

## 🗄 Notebooks

- [1.0-eda.ipynb](notebooks/1.0-eda.ipynb)

## 📦 Folder Structure

    ├── data
    │   └── raw            <- The original, immutable data dump.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │
    ├── notebooks          <- Jupyter notebooks used during the development
    │
    ├── resources          <- figures, images, manuals, and all other explanatory materials.
    │
    ├── .gitignore         <- Files not to be included on GitHub repo
    ├── LICENSE            <- Licensing rights.
    ├── README.md          <- Top-level README for developers.
    ├── poetry.lock        <- file with poetry packages from the environment
    ├── pyproject.toml     <- file with poetry specifications for the project environment