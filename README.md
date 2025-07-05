# 🏡 House Price Prediction

This project is a machine learning pipeline designed to predict house prices based on various features. It leverages data preprocessing, feature engineering, model training, and evaluation using scikit-learn and pandas.

## 📌 Project Overview

The goal of this notebook is to build a regression model that accurately predicts the price of houses. The dataset includes features such as square footage, number of bedrooms, number of bathrooms, etc.

The main steps of the pipeline include:

- Loading and exploring the dataset
- Preprocessing data (handling missing values, encoding categorical variables)
- Feature selection and engineering
- Training regression models (Linear Regression, Random Forest)
- Model evaluation using metrics like R² and RMSE

## 🧠 Algorithms Used

- **Linear Regression**
- **Random Forest Regressor**

## 🗂️ File Structure

```
HousePricePrediction/
│
├── HousePricePrediction.ipynb  # Jupyter Notebook with full analysis
├── README.md                   # Project documentation (you are here)
└── data/                       # (optional) directory for CSV or input files
```

## 📊 Dataset

The dataset used in this project contains various house-related features such as:

- `bedrooms`
- `bathrooms`
- `sqft_living`
- `sqft_lot`
- `floors`
- `waterfront`
- `condition`
- `grade`
- `zipcode`
- `price` (target variable)

## 🚀 Getting Started

### Prerequisites

Make sure the following packages are installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Running the Notebook

1. Clone this repository.
2. Open `HousePricePrediction.ipynb` in Jupyter Notebook or VSCode.
3. Run each cell sequentially.

## 📈 Evaluation Metrics

- **R² Score**: Measures the proportion of variance explained by the model.
- **RMSE (Root Mean Squared Error)**: Indicates the average prediction error.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve this project.

## 📄 License

This project is open-source and available under the MIT License.
