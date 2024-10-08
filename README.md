# CodSoft 💻

This repository contains five data science projects implemented using Python and Streamlit. Each project demonstrates different aspects of machine learning and data analysis.

## Projects

1. Iris Data Classification
2. Movie Review Prediction
3. Credit Card Fraud Detection
4. Sales Prediction
5. Titanic Survival Prediction

## Technologies Used

- Python 3.8+
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Plotly
- Matplotlib
- Seaborn

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Git-me-Harish/CodSoft.git
   cd CodSoft
   ```
2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Project Descriptions and Usage

### 1. Iris Data Classification

This project classifies Iris flowers into three species based on their sepal and petal measurements.

To run the Iris Data Classification app:
```
streamlit run Iris.py
```

Features:
- Data visualization of Iris dataset
- Training of multiple classification models
- Interactive prediction of Iris species

### 2. Movie Review Prediction

This project predicts movie ratings based on various features such as year, duration, and genre.

To run the Movie Review Prediction app:
```
streamlit run movie.py
```

Features:
- Data preprocessing and visualization of movie dataset
- Training of regression models (Linear Regression, Random Forest, XGBoost)
- Interactive prediction of movie ratings

### 3. Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning techniques.

To run the Credit Card Fraud Detection app:
```
streamlit run credit.py
```

Features:
- Handling imbalanced dataset
- Training of classification models for fraud detection
- Interactive prediction of transaction legitimacy

### 4. Sales Prediction

This project predicts sales based on advertising spend across different channels (TV, Radio, Newspaper).

To run the Sales Prediction app:
```
streamlit run sales.py
```

Features:
- Interactive data exploration with visualizations
- Polynomial regression model for sales prediction
- Feature importance analysis
- Real-time sales predictions based on user input

### 5. Titanic Survival Prediction

This project predicts the likelihood of survival for passengers on the Titanic based on various features such as age, sex, passenger class, and more.

To run the Titanic Survival Prediction app:
```
streamlit run Titanic.py
```

Features:
- Advanced data preprocessing and feature engineering
- Training of multiple classification models (Logistic Regression, Random Forest, XGBoost)
- Interactive prediction of survival probability
- Visualization of feature importance and survival statistics
- Detailed interpretation of prediction results

## Data

Each project requires its respective dataset:
- Iris Data Classification: `IRIS.csv`
- Movie Review Prediction: `IMDb Movies India.csv`
- Credit Card Fraud Detection: `creditcard_data.csv`
- Sales Prediction: `advertising.csv`
- Titanic Survival Prediction: `Titanic-Dataset.csv`

Ensure these files are present in the same directory as their corresponding Python scripts.

## Contributing

Contributions to improve the projects are welcome. Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to the Scikit-learn and Streamlit communities for their excellent documentation and examples.
- Dataset sources: UCI Machine Learning Repository, IMDb, Kaggle, Titanic dataset providers
- Special thanks to CodSoft for the project inspiration and support
