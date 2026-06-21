# 🏠 House Price Prediction System

## 📌 Project Title

**House Price Prediction System** — A supervised Machine Learning project that predicts
residential property prices based on physical and structural attributes using three
regression techniques.

---

## 🎯 Objectives

- Perform complete Exploratory Data Analysis (EDA) on a real-world housing dataset
- Preprocess data by handling missing values, encoding, and feature scaling
- Train and compare three regression models: Linear, Polynomial, and Ridge Regression
- Evaluate models using RMSE, MAE, and R² Score
- Visualize results with professional plots
- Document the full ML pipeline for academic submission

---

## ✨ Main Features

- ✅ Automatic synthetic dataset generation if Kaggle CSV is not available
- ✅ Complete EDA — shape, statistics, histograms, scatter plots, heatmap, outliers
- ✅ Data preprocessing — missing values, one-hot encoding, StandardScaler
- ✅ Three trained models with side-by-side performance comparison
- ✅ 10 plots auto-saved to the `plots/` folder
- ✅ Model results saved to `outputs/model_comparison.csv`

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                              |
|-----------------|--------------------------------------|
| Python 3.10+    | Core programming language            |
| pandas          | Data loading and manipulation        |
| NumPy           | Numerical computations               |
| Matplotlib      | Data visualization                   |
| Seaborn         | Statistical plots and heatmaps       |
| scikit-learn    | ML models, preprocessing, evaluation |
| Jupyter         | Interactive notebook environment     |
| VS Code         | Development IDE                      |

---

## 📁 Project Structure

```
house_price_prediction/
│
├── data/
│   └── Housing.csv          ← Place Kaggle dataset here
│
├── plots/                   ← 10 PNG plots saved here automatically
│
├── outputs/
│   └── model_comparison.csv ← Model results table
│
├── main.ipynb               ← Complete project notebook
├── requirements.txt         ← All dependencies
└── README.md                ← This file
```

---

## 🚀 How to Run

**Step 1 — Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 2 — Add the dataset**
Download `Housing.csv` from Kaggle and place it inside the `data/` folder:
> https://www.kaggle.com/datasets/harishkumardatalab/house-price-prediction

> **Note:** If the CSV is missing, the notebook automatically generates
> a synthetic dataset so you can still run all cells.

**Step 3 — Open and run the notebook**
```bash
jupyter notebook main.ipynb
```
Or open `main.ipynb` in VS Code and click **Run All**.

---

## 📊 Models Used

| Model                 | Description                              |
|-----------------------|------------------------------------------|
| Linear Regression     | Baseline — fits a straight line          |
| Polynomial Regression | Captures non-linear relationships (degree=2) |
| Ridge Regression      | Regularized — prevents overfitting       |

---

## 📈 Results

| Rank | Model                 | RMSE      | MAE       | R² Score |
|------|-----------------------|-----------|-----------|----------|
| 🥇 1 | Ridge Regression      | 446,790   | 355,641   | 0.6431   |
| 🥈 2 | Linear Regression     | 447,072   | 355,964   | 0.6427   |
| 🥉 3 | Polynomial Regression | 499,411   | 398,799   | 0.5541   |

**Best Model: Ridge Regression** with R² = 0.64
(explains 64% of house price variation)

---

## 📋 Evaluation Metrics

- **RMSE** — Average prediction error (penalizes large mistakes more)
- **MAE** — Average prediction error (treats all mistakes equally)
- **R² Score** — Proportion of price variation explained by the model (higher = better)

---

*Artificial Intelligence — Software Engineering Department — IIUI-ISB*
