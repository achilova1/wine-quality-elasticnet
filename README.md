
# 🍷 Wine Quality Prediction Using ElasticNet Regression

This project aims to predict the quality of wine using chemical properties from the [Wine Quality dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) and machine learning techniques. Specifically, we implement **ElasticNet Regression**, a linear model that combines both L1 (Lasso) and L2 (Ridge) penalties.

## 📁 Project Structure

- `Wine_Quality_Prediction_Using_ElasticNet_Regression.ipynb`: Main Jupyter Notebook with full EDA, preprocessing, modeling, and evaluation steps.
- `winequality-red.csv`: Dataset used (available from UCI Machine Learning Repository).

## 📊 Features Used

The dataset includes the following physicochemical attributes:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

Target variable: **Quality** (score between 0 and 10)

## 🔍 Methodology

1. **Data Preprocessing**:
   - Checked for missing values
   - Feature scaling using StandardScaler

2. **Modeling**:
   - Used `ElasticNetCV` from Scikit-learn to find the best combination of alpha and l1_ratio.
   - Compared performance with other regression models (optional step if included).

3. **Evaluation**:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

## 📌 Requirements

Make sure to install the following libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🧠 Key Learnings

- ElasticNet helps in situations with multicollinearity and when we want to balance sparsity and stability.
- Regularization can significantly improve the generalization of linear models.

## 📈 Example Output

Model Performance:
- MAE: _x.xx_
- MSE: _x.xx_
- R² Score: _x.xx_

## 📚 References

- UCI Machine Learning Repository - Wine Quality Dataset
- Scikit-learn documentation on [ElasticNet](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.ElasticNet.html)

---

Feel free to clone, use, or modify this project. If you find it helpful, ⭐️ the repo!
