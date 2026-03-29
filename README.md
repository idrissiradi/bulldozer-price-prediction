# 🚜 Bulldozer Price Prediction

Predict the sale price of heavy equipment at auction using historical sales data from Kaggle's [Bluebook for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview) competition.

> **Goal**: Minimize RMSLE (Root Mean Squared Log Error) between predicted and actual auction sale prices.

---

## 📁 Project Structure

```text
bulldozer-price-prediction-project/
├── data/                    # Not tracked by git; add Kaggle data here if running locally
├── main.ipynb               # Main notebook for EDA, preprocessing, and modeling
├── requirements.txt         # Runtime dependencies
├── requirements-dev.txt     # Jupyter development dependencies
├── .gitignore
└── README.md
```

---

## ⚙️ Setup

Install the dependencies:

```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

Launch Jupyter and open the notebook:

```bash
jupyter notebook
```

---

## 📊 Dataset

This project uses the dataset from Kaggle's **Bluebook for Bulldozers** competition. The data includes historical auction sales with 50+ features such as machine configuration, usage, and sale details.

Download the competition files separately and keep them out of version control. The repo's `.gitignore` already excludes `data/`.

Recommended local layout:

```text
data/
├── TrainAndValid.csv
├── Test.csv
└── Data Dictionary.xlsx
```

Note: the current notebook includes Google Colab cells and reads from a Google Drive path (`/content/drive/...`). If you want to run it locally from the `data/` folder, update those notebook paths accordingly.

---

## 📚 References

- [Kaggle Competition Overview](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview)
- [Competition Data Download Page](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data)
- [Data Dictionary.xlsx](data/Data%20Dictionary.xlsx)

---
