# 🚜 Bulldozer Price Prediction
 
Predicting the sale price of heavy equipment at auction using historical sales data. Based on the [Kaggle Bluebook for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview) competition.
 
> **Goal**: Minimize the RMSLE (Root Mean Squared Log Error) between predicted and actual auction sale prices.
 
---
 
## 📁 Project Structure
 
```
bulldozer-price-prediction/
├── data/                        # Not tracked by git (see Data section)
│   ├── TrainAndValid.csv        # Training and validation data
│   ├── Test.csv                 # Test data (no SalePrice)
│   └── Data Dictionary.xlsx     # Feature descriptions
├── main.ipynb                   # Main notebook (EDA, preprocessing, modeling)
├── .gitignore
└── README.md
```
 
---

### Install dependencies

```bash
pip install -r requirements.txt
pip install -r requirements-dev.txt
```

---

## 📊 Dataset
 
The dataset comes from Kaggle's **Bluebook for Bulldozers** competition. It contains historical auction sales of heavy construction equipment with 50+ features including machine configuration, usage, and sale details.

#### Place files in the data/ folder

> ⚠️ Data files are excluded from this repo (exceed GitHub's 100MB limit). You must download them separately.
 
---

## 📚 References
 
- [Kaggle Competition](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview)
- [Data Dictionary]([data/Data%20Dictionary.xlsx](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data))
 
---