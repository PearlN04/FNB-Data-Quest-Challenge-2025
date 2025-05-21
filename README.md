# FNB-Data-Quest-Challenge-2025
Machine learning model to deliver personalized customer offers for FNB using contextual data.

## 🚀 FNB Recommender System — DataQuest 2025
![Recommender System](MLimage.webp) 

## 🌐 Overview
This repository contains my submission for the **FNB DataQuest 2025 Challenge**, where the objective is to build a recommender system that can deliver relevant product offers to customers based on their historical interactions, preferences, and contextual data.

The system is inspired by real-world recommendation engines such as those used by Netflix and Amazon, and is built to enhance FNB’s ability to personalize customer experiences across its digital platforms.

## 🌟 Problem
FNB aims to deliver personalized offers by ranking and recommending the most relevant products for each user. The task is to train a machine learning model that uses contextual and behavioral interaction data to recommend relevant financial products for each customer.

This includes:
- Display, click, and checkout interaction logs
- Item types and descriptions
- User segments and activity levels
- Time-of-day and page context data

## 🎯 Objectives

* **Data Cleaning**: Preprocess and clean raw data including missing values, standardizing formats, and removing irrelevant rows.
* **Feature Engineering**: Generate new meaningful features such as interaction scores, user-item frequencies, and time-based aggregates.
* **Exploratory Data Analysis**: Understand user behavior and item popularity trends.
* **Baseline Recommender**: Build a popularity-based recommender to serve as a benchmark.
* **Collaborative Filtering Model**: Train a recommender model using matrix factorization or hybrid methods.
* **Model Evaluation**: Use accuracy and beyond-accuracy metrics (e.g., Precision@K, Recall@K, Hit Rate) to assess the model.
* **Recommendation Output**: Generate top-N recommendations for users and export to file for interpretation or presentation.

## 📚 Dataset Description

The dataset provided by FNB includes anonymized logs of customer interactions on the platform. Key columns include:

| __Variable__ | __Description__ |
|--------------|------------------|
| `Idcol` | Unique customer identifier |
| `interaction` | Type of interaction: DISPLAY, CLICK, CHECKOUT |
| `int_date` | Date of interaction |
| `item` | Item code (product) interacted with |
| `item_type` | High-level category of the item (e.g., INVEST, LEND, INSURE) |
| `item_descrip` | Description of the item |
| `segment` | Broad income-related customer segment |
| `beh_segment` | Detailed behavioral segment (50 categories) |
| `active_ind` | Customer activity level: Active, Semi Active, Cold Start |
| `page` | Page context of the interaction |
| `tod` | Time-of-day context: Early, Morning, Afternoon, Evening |

## 📁 File Descriptions

- 📓 **`FNB_Recommender_System.ipynb`**: Main notebook containing all preprocessing, modeling, and evaluation steps.
- 📁 **`data/raw/dq_ps_challenge_v2.csv`**: Raw dataset used for model training.
- 📁 **`data/processed/`**: Processed data and recommendation outputs.
- 📘 **`README.md`**: This file — explains the project and how to run it.

## 🚀 Instructions for Local Execution

