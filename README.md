# House_Price_Prediction_D

A machine learning-powered web application that predicts residential property prices based on key housing characteristics. The project combines a trained Random Forest Regressor with a Flask web application, allowing users to obtain real-time house price predictions through an interactive interface.

## 🚀 Features

* Predicts house prices using important property attributes
* Interactive web interface built with Flask
* Real-time prediction generation
* Machine Learning model integration using Scikit-learn
* Data visualization using Chart.js
* User-friendly and responsive design

## 🛠️ Tech Stack

### Backend

* Python
* Flask

### Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Joblib

### Frontend

* HTML
* CSS
* JavaScript
* Chart.js

## 📊 Model Development

### Dataset

* Ames Housing Dataset

### Data Preprocessing

* Missing value handling
* Feature engineering
* Categorical feature encoding
* Feature scaling
* Data cleaning and transformation

### Model

* Random Forest Regressor
* Hyperparameter tuning using RandomizedSearchCV

## 🎯 Input Features

The application predicts house prices based on:

* Overall Quality
* Living Area
* Basement Area
* First Floor Area
* Second Floor Area
* Garage Area
* Year Built
* Full Bathrooms
* Lot Area
* Garage Capacity

## 📂 Project Structure

House_Price_Prediction_Deploy/

├── app.py

├── requirements.txt

├── rf_tuned_model.pkl

├── model_features.pkl

├── templates/

│ └── index.html

└── README.md

## ▶️ Run Locally

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the application

```bash
python app.py
```

4. Open your browser

```text
http://127.0.0.1:5000
```

## 📈 Future Improvements

* Cloud deployment using Render
* Improved UI/UX design
* Advanced feature engineering
* Enhanced prediction visualization
* Batch prediction support

## 👩‍💻 Author

Anjali Bisht
B.Tech (Artificial Intelligence & Machine Learning)
