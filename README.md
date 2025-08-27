# Linear-Regression-From-Scratch-With-Visualizations
"ML models implemented from scratch using NumPy and Pandas only for Training"
# Linear Regression from Scratch on Boston Housing Dataset

This project implements **Linear Regression from scratch** using **Gradient Descent** (without using sklearn's `LinearRegression`), applied to the **Boston Housing dataset**.

The implementation includes:
- Manual weight updates using **Batch Gradient Descent**
- **L2 Regularization** (optional)
- **Loss tracking**
- **Visualizations** (Loss curve, Actual vs Predicted, Residual plot)
- **Performance metrics** (RMSE, R²)
- **Prediction for new data**

---

## 📂 Project Structure

---

## ✅ Features
- **From-Scratch Implementation**: No built-in sklearn linear model used.
- **Training using Gradient Descent**:
  \[
  \hat{y} = XW + b
  \]
- **Loss Function**:
  \[
  L = \frac{1}{n}\sum(y - \hat{y})^2 + \lambda \sum W^2
  \]
- **Evaluation**:
  - **RMSE** (Root Mean Square Error)
  - **R² Score**
- **Visualizations**:
  - Loss vs Epochs
  - Actual vs Predicted
  - Residual Plot
- **Prediction for New House Data**

---

## 📊 Dataset
We use the **Boston Housing dataset** from [OpenML](https://www.openml.org/d/531).

- **Features (13)**: e.g., CRIM (crime rate), RM (rooms per dwelling), LSTAT (% lower status population), etc.
- **Target**: MEDV (Median value of homes in $1000s)

---

## ⚙️ Installation
Clone the repository and install dependencies:
```bash

## 👨‍💻 Author
**anshupatna**  
GitHub: [anshu-pandey](https://github.com/anshu-pandey)
git clone https://github.com/your-username/linear-regression-scratch.git
cd linear-regression-scratch
pip install numpy pandas matplotlib scikit-learn
