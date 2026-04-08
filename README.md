# Wine Quality Predictor

A Flask web application that predicts the quality of wine based on its chemical properties using a trained machine learning model.

---

## Project Structure

Wine-quality-predictor/
* model/
  * wine_quality_model.pkl   # Trained machine learning model
  * scaler.pkl               # Scaler for input features
* templates/
  * index.html               # Flask app HTML template
* app.py                     # Flask app to serve predictions
* requirements.txt           # Python dependencies
* procfile.txt               # For Heroku deployment
* runtime.txt                # Python version for deployment
* venv310/                   # Optional virtual environment folder
* .gitignore                 # Git ignore file
* README.md                  # Project documentation

---

## Features

* Predict wine quality based on chemical properties.
* Web interface using Flask.
* Input scaling handled with saved `scaler.pkl`.
* Deployment ready for Heroku or local server.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Ghayas0772/wine-quality-predictor.git
cd wine-quality-predictor
