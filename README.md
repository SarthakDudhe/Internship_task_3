
# 🏠 House Price Predictor using Linear Regression

This project uses **Linear Regression** to predict house prices based on various features such as area, number of bedrooms, bathrooms, and amenities.

## 📂 Dataset
The dataset contains 545 entries with the following features:
- `price` (target)
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

## 🧠 Model Approach

1. **Data Preprocessing**
    - Handled categorical variables using one-hot encoding
    - Applied log transformation to the target (`price`) for normalization
    - Scaled numerical features using `StandardScaler`

2. **Model Training**
    - Used **Ridge Regression**, a regularized form of linear regression
    - Achieved an R² score of ~0.658 and RMSE ≈ ₹13.15 Lakhs

3. **Prediction**
    - Allows predicting price from features such as area, rooms, and other amenities

## 🚀 How to Use

1. Clone the repository
2. Install required packages (`pandas`, `scikit-learn`, `numpy`)
3. Run the Jupyter notebook or script to train the model and make predictions

## 📊 Example Prediction
Given:
- Area: 5000 sqft
- 3 Bedrooms, 2 Bathrooms, 2 Stories, 1 Parking spot
- Located on main road, has basement and AC
- Furnishing: Semi-furnished

**Predicted Price**: ₹70.2 Lakhs

## 📦 Future Enhancements
- Deploy as a web app using Streamlit or Flask
- Add model comparison (Ridge vs Lasso vs Linear)
- Incorporate feature selection and tuning

---

© 2025 | House Price Predictor - Linear Regression | By Harry Op
"""

# Save to file
readme_path = "/mnt/data/README_HousePricePredictor.md"
with open(readme_path, "w") as file:
    file.write(readme_content)

readme_path




