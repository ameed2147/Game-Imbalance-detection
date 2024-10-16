# Enhanced Game Balancing Through Machine Learning
## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Project Overview
This project focuses on using **machine learning** techniques to enhance game balancing in **competitive multiplayer games**, specifically **Dota 2**. The objective is to detect and address gameplay imbalances by analyzing large datasets of match data, providing valuable insights for game developers to improve **player experience** and **retention**.

## Features
- **Data Collection**: Utilized the **OpenDota API** to collect data from over **10,000 Dota 2 matches**.
- **Machine Learning Models**:
  - **Logistic Regression** for detecting gameplay imbalances.
  - **Random Forest** and **Gradient Boosting** for evaluating feature importance.
  - **Isolation Forest** for identifying anomalies in hero performance and item usage.
- **Key Metrics**: Analyzed factors like **KDA ratio**, **win rate**, **hero combinations**, and **item builds** to highlight significant gameplay imbalances.
- **Anomaly Detection**: Detected outlier heroes and items that showed abnormal performance, helping improve game balance.

## Project Structure

```bash
.
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks for exploratory data analysis
├── src/                # Source code for data collection, preprocessing, and model training
│   ├── data_collection.py     # OpenDota API data collection script
│   ├── preprocessing.py       # Data preprocessing and feature extraction
│   ├── model_training.py      # Machine learning model training and evaluation
│   ├── anomaly_detection.py   # Scripts for anomaly detection using Isolation Forest
├── results/            # Visualizations and analysis results
├── README.md           # Project documentation (this file)
├── requirements.txt    # Python dependencies
└── LICENSE             # License for the project



