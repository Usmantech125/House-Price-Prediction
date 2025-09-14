
# 🏡 House Price Prediction 

In this project the goal is to build a **regression model** to predict house prices based on various features such as area, number of bedrooms, availability of amenities, and more.

---

## 📌 Problem Statement

Given a housing dataset, build a machine learning model to **predict house prices** using features like:
- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main road access, guest room, basement
- Air conditioning, hot water heating
- Furnishing status, preferred area

---

## 🧰 Tools & Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Linear Regression
- StandardScaler
- Train-Test Split
- RMSE & R² Score Evaluation

---

## ⚙️ Preprocessing Steps

1. **One-Hot Encoding** of categorical variables (`mainroad`, `guestroom`, `furnishingstatus`, etc.)
2. **Log Transformation** of the target variable `price` for normalization
3. **Feature Scaling** using `StandardScaler`
4. **Train-Test Split** (80/20)

---

## 📈 Model & Evaluation

- **Model Used:** Linear Regression  
- **Evaluation Metrics:**
  - Mean Squared Error (MSE): `0.0633`
  - R² Score: `0.6722` (Good fit for a linear model)

---

## ✅ Results

- The linear regression model shows a decent ability to generalize, explaining over **67%** of the variance in house prices.
- The dataset is now ready for further experimentation with advanced models (e.g., Random Forest, XGBoost).

---

## 🔗 Repository Contents

- `Housing.csv`: Input dataset
- `HousePricePrediction.ipynb`: Main notebook
- `README.md`: Project overview and documentation

---


