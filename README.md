# 🌫️ OAQJP Final Project – Embedded AI for Air Quality Prediction

**Machine Learning Model for Forecasting Air Quality Metrics**  
Built with Scikit-learn · Pandas · Python · Embedded AI Concepts

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![ML Model](https://img.shields.io/badge/Model-RandomForest%2C%20LinearRegression-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-lightgrey.svg)

## 📘 Overview

This project is the final submission for the OAQJP Embedded AI track. It explores air quality prediction using supervised machine learning models trained on sensor data. The goal is to deploy lightweight models suitable for embedded systems, enabling real-time environmental monitoring.

## 🔍 Features

- 📈 Predicts PM2.5, PM10, and other air quality indicators
- 🧠 Implements Random Forest and Linear Regression models
- 🧪 Includes preprocessing pipeline for sensor data
- 📦 Structured for deployment on embedded platforms

## 📁 Project Structure

```bash
oaqjp-final-project-emb-ai/
├── data/               # Raw and cleaned air quality datasets
├── models/             # Saved model files (e.g., .pkl)
├── notebooks/          # Jupyter notebooks for EDA and training
├── src/                # Core scripts for preprocessing and inference
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/frankTheCodeBoy/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```

2. **Set up a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

Run the model inference script:
```bash
python src/predict.py --input data/test_sample.csv
```

Or explore the training pipeline via Jupyter:
```bash
jupyter notebook notebooks/model_training.ipynb
```

## 📊 Sample Output

```text
Predicted PM2.5: 42.7 µg/m³
Predicted PM10: 76.3 µg/m³
Air Quality Index: Moderate
```

## 📄 License

This project is licensed under the [MIT License](LICENSE). You’re free to use, modify, and distribute it with proper attribution.

## 🧠 Acknowledgments

- OAQJP Embedded AI Track
- Sensor data sourced from open air quality datasets

## 📬 Contact

**Frank** – [GitHub Profile](https://github.com/frankTheCodeBoy)

---

