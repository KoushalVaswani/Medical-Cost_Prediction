# Medical Cost Prediction using Machine Learning

This project predicts the **Annual Medical Cost** of an individual based on various demographic, health, and insurance-related features. It implements and compares **Linear Regression** and **Random Forest Regressor** models to find the most accurate prediction algorithm.

---

## 🚀 Project Overview
Predicting medical expenses is crucial for insurance companies and individuals alike. This project performs thorough data preprocessing (Handling Missing Values, One-Hot Encoding, Label Mapping, and Feature Scaling) and applies Machine Learning algorithms to achieve high-accuracy cost predictions.

### Key Features Analyzed:
*   **Demographics:** Age, Gender, City Type.
*   **Health Metrics:** BMI, Smoker Status, Diabetes, Hypertension, Heart Disease, Asthma.
*   **Lifestyle & Logs:** Daily Steps, Sleep Hours, Stress Level, Physical Activity Level.
*   **Insurance Data:** Insurance Type, Insurance Coverage Percentage, Previous Year Cost.

---

## 📊 Model Performance & Results

After evaluating both models on the test dataset, the **Random Forest Regressor** significantly outperformed the baseline Linear Regression model by successfully capturing non-linear relationships.

| Evaluation Metric | Linear Regression | Random Forest Regressor | Status |
| :--- | :---: | :---: | :---: |
| **$R^2$ Score (Accuracy)** | `0.9282` (~92.8%) | **`0.9534` (~95.3%)** | **Improved!** 🚀 |
| **Mean Absolute Error (MAE)** | `519.61` | **`454.35`** | **Reduced!** 📉 |
| **Root Mean Squared Error (RMSE)** | - | **`631.81`** | **Optimized!** |
| **Mean Absolute Percentage Error (MAPE)** | - | **`10.14%`** | **Highly Accurate!** |

### Key Takeaway:
The **Random Forest** model delivers an outstanding **MAPE of 10.14%**, meaning its predictions are, on average, ~90% accurate to the actual medical cost.

---

## 🛠️ Tech Stack & Libraries Used
*   **Language:** Python 3
*   **Environment:** Google Colab / Jupyter Notebook
*   **Data Libraries:** Pandas, NumPy
*   **Visualization:** Matplotlib, Seaborn
*   **Machine Learning:** Scikit-Learn (`StandardScaler`, `LinearRegression`, `RandomForestRegressor`)

---

## 📋 How to Run the Project

1. **Clone the Repository:**
```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
