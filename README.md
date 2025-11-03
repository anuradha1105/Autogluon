# 🧠 AutoGluon Colabs — Data Mining Assignment

This repository demonstrates **AutoGluon** for multiple machine learning tasks:
- **Kaggle IEEE-CIS Fraud Detection** — binary classification  
- **California Housing Prices** — regression  
- Official AutoGluon tutorials — Quick Start, In-Depth, Multimodal Tabular, and Automatic Feature Engineering  


---

## 🚀 Open in Google Colab

| Notebook | Description | Open in Colab |
|-----------|--------------|---------------|
| 🧩 01 IEEE Fraud Detection | Binary classification on Kaggle dataset | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/01_ieee-fraud-autogluon.ipynb) |
| 🏠 02 California Housing Prices | Regression demo using scikit-learn dataset | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/02_california-housing-autogluon.ipynb) |
| ⚡ B1 Tabular Quick Start | Basic AutoGluon Tabular workflow | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/B1_tabular-quickstart.ipynb) |
| 🧠 B2 Tabular In-Depth | Stacking / ensembling & feature importance | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/B2_tabular-indepth.ipynb) |
| 🧬 B3 Multimodal Tabular | Combines categorical + text features | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/B3_tabular-multimodal.ipynb) |
| 🔧 B4 Automatic Feature Engineering | AutoGluon’s automatic feature generation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anuradha1105/Autogluon/blob/main/colabs/B4_tabular-feature-engineering.ipynb) |

---


### 1️⃣ IEEE Fraud Detection (Tabular Classification)
- **Notebook:** [`colabs/01_ieee-fraud-autogluon.ipynb`](colabs/01_ieee-fraud-autogluon.ipynb)
- **Goal:** Predict fraudulent transactions using AutoGluon.
- **Artifacts:** Leaderboard, feature importance, and submission CSVs under [`artifacts/`](artifacts/)
- **Note:** Kaggle API access is archived; notebook includes fallback dataset for reproducibility.

### 2️⃣ California Housing (Regression)
- **Notebook:** [`colabs/02_california-housing-autogluon.ipynb`](colabs/02_california-housing-autogluon.ipynb)
- **Goal:** Predict California house prices using AutoGluon Tabular Predictor.
- **Artifacts:** Leaderboard and feature importance CSVs under [`artifacts/`](artifacts/)

### 🧠 Tools Used
- Python (Colab)
- AutoGluon 1.4.0
- Scikit-learn datasets
- Pandas, NumPy

## 🚀 Overview

AutoGluon is an open-source AutoML library from AWS that automatically handles:
- 🔍 Data preprocessing, feature encoding, and feature engineering  
- 🤖 Model training, hyperparameter optimization, and ensembling  
- 📊 Leaderboards, evaluation metrics, and model explainability  

All notebooks below were run in Colab and checked in with **outputs visible** for reproducibility.

---

| 🔧 **B4 Automatic Feature Engineering** | Showcases AutoGluon’s **automatic feature generator**. It creates, transforms, and prunes features for better accuracy. <br>💡 Cells: install → load data → auto-feature gen → train → feature report → save. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/tabular/tabular-feature-engineering.ipynb) |

---

## 🏁 How to Run

```bash
# in Colab or local
!pip install autogluon
```

Then open any notebook and run cells sequentially.  
Each notebook is independent and self-contained.

---

## 📦 Artifacts and Outputs
- Model artifacts are saved to `autogluon/outputs/`  
- Example files:
  - `ieee_fraud_submission.csv`
  - `california_leaderboard.csv`
  - `california_test_predictions.csv`

---










 

