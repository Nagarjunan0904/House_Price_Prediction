# 🏡 House Price Prediction Using Machine Learning

This project aims to predict house prices using the Ames Housing Dataset, a rich and real-world dataset containing various features about residential homes in Ames, Iowa.

---

## 📌 Objective

To build and evaluate a regression model that can predict the sale price of houses based on features such as size, quality, location, and condition.

---

## 📁 Dataset

**Source**: [Ames Housing Dataset - Kaggle](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)  
**Rows**: 2,930  
**Columns**: 82 features, including:
- Categorical variables (e.g., Neighborhood, House Style)
- Numerical variables (e.g., Lot Area, Year Built)
- Target variable: `SalePrice`

---

## 🧪 ML Workflow

1. **Problem Definition**  
   Predict the continuous variable `SalePrice` using regression.

2. **Data Exploration (EDA)**  
   - Understand distributions and missing values
   - Identify key predictors (e.g., `Gr Liv Area`, `Overall Qual`)

3. **Preprocessing**
   - Dropped high-missing columns
   - Imputed remaining missing values
   - Encoded categorical variables
   - Split into train/test sets
   - Scaled numerical features (for linear models)

4. **Modeling**  
   - Model used: `Linear Regression`
   - Trained on 80% of the data, tested on 20%

5. **Evaluation Metrics**  
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

6. **Visualization**  
   - Scatter plot of actual vs predicted prices

---

## ✅ Results

- The Linear Regression model performed well with reasonable R² and RMSE.
- The strongest predictors included `Gr Liv Area`, `Overall Qual`, and `Garage Cars`.

---

## 🔍 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Perform feature selection and engineering
- Deploy using Streamlit or Flask

---

## 🛠 Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

---

## 📎 Usage

```bash
# Clone this repo
git clone https://github.com/your-username/house-price-prediction.git

# Install requirements
pip install -r requirements.txt

# Run notebook
jupyter notebook house_price_prediction.ipynb
