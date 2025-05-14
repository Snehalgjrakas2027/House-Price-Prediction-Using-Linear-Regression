# 🏡 House Price Prediction Using Linear Regression

This project demonstrates how to use **Linear Regression** to predict house prices based on various features such as size, number of bedrooms, location, and more.

## 📌 Objective

To develop a machine learning model that accurately predicts the price of a house given specific input features. This project utilizes **Linear Regression**, one of the most fundamental algorithms in supervised learning.

## 📊 Dataset

The dataset includes various attributes of houses such as:

* Size (in square feet or square meters)
* Number of bedrooms
* Number of bathrooms
* Location (could be categorical or encoded)
* Age of the house
* Lot size
* Other optional features (e.g., garage, pool, etc.)

> *Note: Make sure to preprocess the dataset for missing values, normalization, and encoding of categorical variables.*

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (for visualization)

## 🧪 Steps to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main script**

   ```bash
   python main.py
   ```

4. **View the output**

   * The model will output predicted prices for test data.
   * Evaluation metrics like **R² score**, **Mean Squared Error (MSE)**, and **Mean Absolute Error (MAE)** will also be shown.

## 📈 Model Evaluation

The model is evaluated using:

* **R² Score** – Measures how well the regression predictions approximate the real data points.
* **MSE** – Measures the average squared difference between the predicted and actual values.
* **MAE** – Measures the average absolute difference.

```

## 🚀 Future Improvements

* Use advanced models like Ridge, Lasso, or Random Forest for comparison.
* Add hyperparameter tuning using GridSearchCV.
* Deploy the model using a web framework like Flask or FastAPI.

