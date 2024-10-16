# 🎮 Enhanced Game Balancing Through Machine Learning

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## 🌟 Project Overview
This project focuses on using **machine learning** techniques to enhance game balancing in **competitive multiplayer games**, specifically **Dota 2**. The objective is to detect and address gameplay imbalances by analyzing large datasets of match data, providing valuable insights for game developers to improve **player experience** and **retention**.

## 🔍 Features
- **Data Collection**: Utilized the **OpenDota API** to collect data from over **10,000 Dota 2 matches**.
- **Machine Learning Models**:
  - **Logistic Regression** for detecting gameplay imbalances.
  - **Random Forest** and **Gradient Boosting** for evaluating feature importance.
  - **Isolation Forest** for identifying anomalies in hero performance and item usage.
- **Key Metrics**: Analyzed factors like **KDA ratio**, **win rate**, **hero combinations**, and **item builds** to highlight significant gameplay imbalances.
- **Anomaly Detection**: Detected outlier heroes and items that showed abnormal performance, helping improve game balance.

## 🛠️ Methodology

### 📊 Data Collection:
- Gathered over **10,000 player records** from Dota 2 using the **OpenDota API**.

### 🧹 Data Preprocessing:
- Cleaned and preprocessed the data by removing null values, normalizing, and extracting key features like **KDA ratio**, **hero combinations**, and **item builds**.

### 📈 Machine Learning Models:
- **Logistic Regression** to detect imbalances in gameplay.
- **Random Forest** and **Gradient Boosting** to analyze feature importance and predict game outcomes.
- **Isolation Forest** to detect anomalies in hero and item performance.

## 🔑 Key Findings

- **Top Factors for Winning**: Key metrics such as **KDA ratio**, **tower damage**, and **hero statistics** showed the highest correlation with winning.
- **Meta Heroes**: Heroes like **Axe**, **Phantom Lancer**, and **Rubick** were identified as dominant, with higher win rates and KDAs.
- **Anomalies**: Heroes such as **Juggernaut**, **Zeus**, and **Tinker** were identified as potential outliers due to their frequent dominance, suggesting they may need balancing.

## 🚀 Future Work
- Expand the methodology to include other game genres, such as **FPS** and **RTS**.
- Explore more advanced machine learning models like **deep learning** to improve imbalance detection.
- Integrate more complex gameplay statistics for deeper analysis.

## 🤝 Contributing
If you'd like to contribute, please fork the repository and create a pull request. For any major changes, please open an issue first to discuss your proposed changes.

## 🙏 Acknowledgments
Special thanks to my supervisor **Dr. Asim Ali** for his invaluable guidance and support throughout the project. This project was made possible by the **OpenDota API**, which provided access to comprehensive Dota 2 match data.
