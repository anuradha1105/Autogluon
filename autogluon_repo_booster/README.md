# AutoGluon Colabs — Data Mining Assignment

This repository demonstrates AutoGluon across classification, regression, multimodal tabular, and automatic feature engineering. It also includes a Kaggle-ready pipeline for the **IEEE-CIS Fraud Detection** competition and a **California Housing** regression demo.

## 📂 Structure
```
colabs/
  01_ieee-fraud-autogluon.ipynb
  02_california-housing-autogluon.ipynb
  B1_tabular-quickstart.ipynb
  B2_tabular-indepth.ipynb
  B3_tabular-multimodal.ipynb
  B4_tabular-feature-engineering.ipynb
artifacts/            # leaderboards, feature importances, predictions, submissions
data/                 # local data workspace (ignored by git except .gitkeep)
```
> If a folder is missing, create it (Add file ▸ Create new file) and place a `.gitkeep` inside.

## ▶️ How to Run in Google Colab
1. Open any notebook in **Google Colab**.
2. Run the top **Common Setup** cell (installs `autogluon>=1.0` and creates folders).
3. For **Kaggle** notebooks, upload your `kaggle.json` (Kaggle ▸ Account ▸ Create New API Token).
4. **Run all cells**.
5. In Colab: **Edit ▸ Notebook settings ▸ uncheck** “Omit code cell output when saving”.
6. **File ▸ Save a copy in GitHub…** and select this repo to push the notebook **with outputs**.

## 🗂 Artifacts Saved
- `artifacts/*leaderboard.csv`
- `artifacts/*feature_importance.csv`
- `artifacts/ieee_fraud_submission.csv` (Kaggle submission file)

## ✅ Grader Notes
- All notebooks include exported artifacts to prove execution.
- IEEE fraud notebook produces a valid `submission.csv` with columns: `TransactionID,isFraud`.

## 🔧 Dependencies
- Python 3.x, Google Colab
- `autogluon>=1.0`, `kaggle`

## 📜 License
Educational use.
