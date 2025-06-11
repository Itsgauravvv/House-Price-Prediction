# 🏠 House Price Prediction Web App

A web-based application that predicts housing prices in Boston using machine learning. Built with Python, Flask, and a responsive Bootstrap UI, this app takes in various housing features and returns an estimated price.

---

## 🚀 Features

- 🧠 Machine learning model trained on the Boston Housing Dataset
- 🌐 Flask-powered backend with HTML templating
- 📊 Takes 13 inputs (like CRIM, RM, TAX, etc.)
- 🎯 Predicts house price with a single click

---

## 🖥️ Demo

https://github.com/Itsgauravvv/House-Price-Prediction/assets/demo.gif *(Add GIF here if you have one)*

---

## 🛠️ Technologies Used

- **Python** 🐍
- **Flask** 🌐
- **HTML5 + CSS3 + Bootstrap** 🎨
- **scikit-learn** 🔍
- **Pandas & NumPy** 📊
- **Jinja2 Templates**

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Itsgauravvv/House-Price-Prediction.git
   cd House-Price-Prediction
2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate     # For Windows
3. **Install dependencies**
   ```bash
   pip install requirements.txt
4. **Run the app**
   ```bash
   python app.py
5. **Visit Localhost**
   [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
6. **Project Structure**
   House-Price-Prediction/
   │
   ├── static/
   │   └── style.css           # Styling (dark theme, animations)
   │
   ├── templates/
   │   └── predict.html        # HTML frontend with Bootstrap
   │
   ├── app.py                  # Main Flask server file
   ├── model.pkl               # Trained machine learning model       
   └── requirements.txt        # Required Python packages

