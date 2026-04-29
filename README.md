![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2.0-orange?style=flat-square)
![TensorFlow](https://img.shields.io/badge/tensorflow-2.10.0-red?style=flat-square)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/Ash905Sections/Stock_Price_Prediction?style=flat-square)
![GitHub Forks](https://img.shields.io/github/forks/Ash905Sections/Stock_Price_Prediction?style=flat-square)

<div align="center">
  <h1> Machine Learning</h1>
  <p><strong>Predict which algorithim in ML acquires 95%+ accuracy using advanced ML models</strong></p>
  <br>
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-features">Features</a> •
  <a href="#-results">Results</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-license">License</a>
</div>

---

## 🎯 Overview

This comprehensive machine learning project builds and compares **four state-of-the-art models** to forecast Tesla stock prices with exceptional accuracy. Leveraging **22 engineered technical indicators** derived from **7 years of historical OHLCV data** (1,692 trading days), the models achieve **95.03% accuracy (R² = 0.9503)** with the winning **Random Forest model**.

### Key Highlights
- ✅ **95.03% Accuracy** — R² Score from Random Forest
- 📊 **22 Feature Engineering** — Technical indicators across 7 categories
- 🤖 **4 Models Compared** — Ridge, RF, GB, and LSTM
- 📈 **7-Year Dataset** — 1,692 trading days of Tesla data
- 📉 **Comprehensive Visualizations** — 6-panel dashboard + 30-day forecast
- 🚀 **Production-Ready Code** — Modular, documented, and scalable

---

## 📊 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Feature Engineering](#-feature-engineering)
- [Models Used](#-models-used)
- [Results](#-results)
- [Visualizations](#-visualizations)
- [Quick Start](#-quick-start)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Architecture](#-project-architecture)
- [How It Works](#-how-it-works)
- [Performance Metrics](#-performance-metrics)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 📈 Dataset

| Property | Details |
|----------|---------|
| **Source** | Tesla (TSLA) Historical Stock Data |
| **Filename** | `Tesla.csv` |
| **Date Range** | 29 June 2010 → 17 March 2017 |
| **Total Rows** | 1,692 trading days |
| **Columns** | 7 — Date, Open, High, Low, Close, Volume, Adj Close |
| **Missing Values** | None (100% complete data) |
| **Data Format** | CSV (Comma-separated values) |
| **File Size** | ~200 KB |

### Dataset Sample
