# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using **Machine Learning** based on various property features such as area, bedrooms, bathrooms, parking, furnishing status, and other amenities.

The project demonstrates the complete machine learning workflow including data preprocessing, visualization, model training, evaluation, and prediction using Linear Regression.

---

# 🎯 Objective

The objective of this project is to build a regression model capable of estimating the selling price of a house based on its characteristics.

---

# 📂 Dataset

The project uses the Housing Prices Dataset containing information about residential properties.

Features include:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

Target Variable:

- House Price

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Jupyter Notebook

---

# 📊 Machine Learning Workflow

```
Dataset

↓

Data Cleaning

↓

Label Encoding

↓

Exploratory Data Analysis

↓

Feature Selection

↓

Train-Test Split

↓

Linear Regression Model

↓

Prediction

↓

Model Evaluation

↓

Save Model (.pkl)
```

---

# 📈 Data Visualization

The project includes several visualizations to better understand the dataset:

- Correlation Heatmap
- House Price Distribution
- Area vs Price
- Actual vs Predicted Prices
- Residual Plot
- Feature Coefficient Plot

---

# 🤖 Machine Learning Model

Algorithm Used:

**Linear Regression**

The model is trained using Scikit-Learn and evaluated using standard regression metrics.

---

# 📊 Evaluation Metrics

The model performance is measured using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📁 Project Structure

```
HousePricePrediction/

│── HousePricePrediction.ipynb
│── house_price_prediction.py
│── dataset.csv

│── house_price_model.pkl
│── label_encoder.pkl

│── correlation_heatmap.png
│── price_distribution.png
│── area_vs_price.png
│── actual_vs_predicted.png
│── residual_plot.png
│── feature_coefficients.png

│── README.md
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/HousePricePrediction-ML.git
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

# ▶️ Run the Project

Open Jupyter Notebook

```bash
jupyter notebook
```

Run

```
HousePricePrediction.ipynb
```

OR run the standalone application:

```bash
python house_price_prediction.py
```

---

# 💻 Example Prediction

Input

```
Area = 7000

Bedrooms = 3

Bathrooms = 2

Stories = 2

Parking = 2

Air Conditioning = Yes
```

Output

```
Estimated House Price

₹ 7,845,000
```

*(Actual prediction may vary depending on the trained model.)*

---

# 📚 Learning Outcomes

Through this project I learned:

- Data preprocessing
- Exploratory Data Analysis
- Feature Encoding
- Regression Algorithms
- Model Evaluation
- Saving and Loading ML Models
- Data Visualization
- End-to-End Machine Learning Pipeline

---

# 🚀 Future Improvements

- Random Forest Regression
- XGBoost Regressor
- Hyperparameter Tuning
- Streamlit Web Application
- Model Deployment

---

# 👨‍💻 Author

**Jitesh Prasad Raskar**

B.Tech Computer Science Engineering

Artificial Intelligence & Machine Learning Internship

---

⭐ If you found this project helpful, feel free to star the repository.
