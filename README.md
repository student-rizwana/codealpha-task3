# code-alpha-task2

## 📌 Project Overview
The **Car Price Prediction** project aims to build a machine-learning model to predict the price of a car based on various features like brand, year, mileage, fuel type, and more. This model helps users estimate car prices accurately using historical data and advanced regression techniques.

## 📊 Dataset
The dataset used for this project contains information about various car features and their corresponding prices. The dataset typically includes the following attributes:

- **Car Name**: The brand and model of the car
- **Year**: Year of manufactur
- **Fuel Type**: Petrol, Diesel, CNG, etc.
- **Transmission**: Manual or Automatic
- **Selling Price**: The actual price of the car (target variable)

## 📈 Project Workflow

1. **Data Collection**: Acquired a dataset of car listings with key attributes.
2. **Data Preprocessing**: Handled missing values, encoded categorical data, and scaled numerical features.
3. **Exploratory Data Analysis (EDA)**: Visualized data trends, feature correlations, and distribution.
4. **Model Selection**: Implemented and compared different regression models:
   - Linear Regression
   - Lasso Regression
   - Decision Tree Regressor
   - Random Forest Regressor
5. **Model Evaluation**: Assessed model performance using:
   - R-squared (R²) Score
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
  

## 📦 Dependencies
Ensure the following packages are installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/student-rizwana/car prediction.git
cd car-price-prediction
```

2. Run the Jupyter Notebook or Python script:

```bash
jupyter notebook car prediction.ipynb
```

OR

```bash
python car prediction.py
```

## 📊 Results
The best-performing model achieved:

- **R-squared Score**: 0.92 (92% accuracy)
- **Mean Absolute Error**: 1200 USD

## 📌 Key Insights
- Mileage and car age significantly impact the car price.
- Automatic cars generally have higher resale values.
- Feature scaling improves model performance.

## 📄 Future Improvements
- Integrate more advanced models (e.g., XGBoost, LightGBM).
- Deploy the model using a Flask or Streamlit web interface.
- Incorporate real-time car listings for dynamic predictions.

## 👨‍💻 Author
[Rizwana Banu Dange](https://github.com/rizwana-student) 


