# 🛒 Smart Cart Predictor  
**Amazon Hackathon Project — Intelligent Price & Demand Forecasting**

> A machine learning–driven solution that predicts smart cart item prices and demand trends using product data and textual descriptions.  
> Built as part of the **Amazon Hackathon**, this project demonstrates an ensemble of LightGBM, Ridge, and RandomForest models optimized for real-world e-commerce insights.

---

## 🚀 Overview

The **Smart Cart Predictor** leverages NLP-based product understanding and advanced regression modeling to predict optimal product prices and trends.  
It utilizes TF-IDF + LightGBM + Ridge + RandomForest ensemble learning for highly accurate forecasting.

---

## 🧠 Tech Stack

| Category | Tools Used |
|-----------|-------------|
| Language | Python 3.10 |
| ML Libraries | LightGBM, scikit-learn, numpy, pandas |
| NLP | TF-IDF Vectorizer, Regex Cleaning |
| IDE | Jupyter Notebook |
| Version Control | Git & GitHub |
| Environment | Conda / pip virtual environment |

---

## 🧩 Key Features

✅ Cleans and preprocesses product descriptions using regex and TF-IDF.  
✅ Uses LightGBM with early stopping for optimal performance.  
✅ Combines Ridge Regression and RandomForest in an ensemble.  
✅ Achieves **low SMAPE (Symmetric Mean Absolute Percentage Error)** and high prediction accuracy.  
✅ Fully modular notebook with explainable steps.

---

## 📁 Project Structure

smart-cart-predictor/
│
├── data/
│ ├── train.csv
│ ├── test.csv
│
├── final_notebook.ipynb # Your main Jupyter Notebook
├── requirements.txt
├── LICENSE
└── README.md

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/saheelyadav/smart-cart-predictor.git
   cd smart-cart-predictor

2. Create Virtual Environment

   python -m venv venv
   venv\Scripts\activate   # On Windows
3. Install Dependencies

   pip install -r requirements.txt


4. Run the Notebook
   Open final_notebook.ipynb in Jupyter or VS Code and execute all cells.

📊 Model Pipeline

Data Cleaning & Preprocessing

Text normalization (regex)

Stopword removal and character repetition handling

Feature Extraction

TF-IDF vectorization on text columns

Model Training

LightGBM (optimized with early stopping)

Ridge Regression

RandomForest Regressor

Ensemble Blending

Weighted average ensemble for final predictions

Evaluation

MAE (Mean Absolute Error)

SMAPE (Symmetric MAPE)

🏆 Hackathon Insights

This project was developed during the Amazon Hackathon 2025, focusing on smart shopping intelligence — predicting demand and optimal pricing through ML-powered insights.

👨‍💻 Contributors

Saheel Yadav — Lead Developer & Asoriring ML Engineer

🪪 License

This project is licensed under the MIT License — see the LICENSE
 file for details.

🌟 Acknowledgments

This project was built as part of the Amazon Hackathon 2025, with the goal of developing an intelligent solution for e-commerce optimization through data-driven insights.

We would like to express our sincere gratitude to:

Amazon Hackathon Organizing Team — for providing a challenging and inspiring platform to apply real-world machine learning skills.

Mentors and Jury Panel — for their valuable feedback, guidance, and encouragement throughout the development phase.

Open-source community — for the amazing tools and libraries that made this project possible (LightGBM, Scikit-learn, Pandas, NumPy, etc.).

Fellow participants and teammates — for their innovative ideas and collaborative spirit that made this hackathon a great learning experience.

This project reflects dedication, countless hours of experimentation, and a passion for solving real-world problems using machine learning and NLP.