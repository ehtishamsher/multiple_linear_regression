# 📈 Multiple Linear Regression Analysis

A machine learning project exploring **Multiple Linear Regression** — using multiple input features to predict a continuous target variable, with full exploratory data analysis, model training, evaluation, and coefficient interpretation.

---

## 📁 Project Structure

```
multiple_linear_regression/
│
├── data/                               # Dataset used for training & analysis
└── multiple_linear_regression.ipynb    # Full EDA + model training notebook
```

---

## ⚙️ How It Works

1. **Data Loading & EDA** — Loaded the dataset, inspected structure, and visualized feature relationships using correlation heatmaps and pair plots
2. **Data Preprocessing** — Handled missing values, encoded categorical variables, and split data into train/test sets
3. **Model Training** — Trained a `LinearRegression` model using Scikit-learn with multiple input features
4. **Evaluation** — Measured model performance using R² Score and RMSE
5. **Coefficient Interpretation** — Analyzed model coefficients to identify which features most influence the target variable

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python 3 |
| ML Library | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook |

---

## 🔧 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/ehtishamsher/multiple_linear_regression.git
cd multiple_linear_regression

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Launch the notebook
jupyter notebook multiple_linear_regression.ipynb
```

---

## 📊 Model Details

- **Algorithm:** Multiple Linear Regression
- **Input Features:** Multiple predictor variables
- **Preprocessing:** Null handling, train/test split
- **Evaluation Metrics:** R² Score, RMSE

---

## 🎯 Key Learnings

- How to handle multiple input features in a regression problem
- Reading and interpreting a correlation heatmap
- The difference between R² and RMSE and when each matters
- How model coefficients explain real-world feature impact

---

## 👤 Author

**Muhammad Ehtisham Khan**  
[GitHub](https://github.com/ehtishamsher) · [LinkedIn](https://www.linkedin.com/in/mohdehtishamkhan/)
