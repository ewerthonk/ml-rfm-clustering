# Mapping E-Commerce Customer Profiles with RFM and K-Means

<div align="center">
  <em>Mapping E-Commerce Customer Profiles with RFM and K-Means.</em>
</div>

<br>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
</div>

## 📖 Project

### 👨🏻‍🏫 Introduction

This is the repo for paper "Mapping E-Commerce Customer Profiles with RFM and K-Means" presented at CoUrb - SBRC 2025 in Natal, RN, Brazil. The project focuses on implementing a scalable **customer segmentation model** for e-commerce retail companies, leveraging the **RFM (Recency, Frequency, Monetary)** methodology and **K-Means clustering**. The goal is to understand online customer behavior dynamics and build a framework to enable e-commerce companies to apply data-driven strategies.

### 🎯 Goals

- Exploratory Data Analysis: explore and reveal initial insisghts about the data.
- RFM Segmentation: Calculate recency, frequency, and monetary values for customer ranking.
- Clustering: Apply K-Means to group customers based on their purchasing behavior.
- Insights: Provide actionable insights to optimize marketing strategies for each customer segment.

## 🗄 Notebooks

- [1.0-eda.ipynb](notebooks/1.0-eda.ipynb)
- [2.0-rfm_default.ipynb](notebooks/2.0-rfm_default.ipynb)
- [3.0-rfm_with_kmeans.ipynb](notebooks/3.0-rfm_with_kmeans.ipynb)
- [4.0-rfm_with_kmeans_and_transformation.ipynb](notebooks/4.0-rfm_with_kmeans_and_transformation.ipynb)

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