🌸 Iris Flower Classifier (Flask + ML Project)
📌 Overview

The Iris Flower Classifier is a simple machine learning web app built with Flask and Python.
It predicts the species of an Iris flower (Setosa, Versicolor, Virginica) based on its sepal length, sepal width, petal length, and petal width.

This is one of the most popular beginner ML projects and a great way to learn how to:

Train and save ML models.

Deploy models in a Flask web app.

Build a clean UI for predictions.

⚙️ Tech Stack

Backend / ML

Python 🐍

Flask (web framework)

Scikit-learn (ML model training)

NumPy & Pandas (data handling)

Joblib (model serialization)

Frontend

HTML5

CSS3 (custom styles, gradient UI)

🚀 How It Works

Train Model

Uses the built-in Iris dataset from scikit-learn.

A Logistic Regression model is trained and saved as iris_model.pkl.

Flask Web App

The user enters flower measurements in a web form.

Flask loads the trained ML model and makes predictions.

The predicted flower type is displayed beautifully in the result page.

Prediction Logic

Input: Sepal Length, Sepal Width, Petal Length, Petal Width

Model outputs:

0 → Setosa

1 → Versicolor

2 → Virginica

📂 Project Structure
iris_flower_classifier/
│
├── model/
│   └── iris_model.pkl          # Saved ML model
│
├── app.py                      # Flask app
├── train_model.py              # Model training script
│
├── templates/
│   ├── index.html              # Input form page
│   └── result.html             # Result page
│
├── static/
│   └── style.css               # CSS styles
│
└── requirements.txt            # Python dependencies

🛠️ Installation & Setup

Clone the repo:

git clone https://github.com/Souparno467/iris.git
cd iris

Install dependencies:

pip install flask scikit-learn pandas numpy joblib


Train the model (runs once):

python train_model.py


Run the Flask app:

python app.py


Open in browser:

http://127.0.0.1:5000/

🎯 Example Inputs

Versicolor

Sepal Length: 6.0

Sepal Width: 2.8

Petal Length: 4.5

Petal Width: 1.5

Virginica

Sepal Length: 6.5

Sepal Width: 3.0

Petal Length: 5.8

Petal Width: 2.2

✨ Future Enhancements

Show probability scores for each flower species.

Add bar chart visualization (Matplotlib).

Deploy on Heroku / Render / Vercel.

Add input validation & error handling.

📜 License

This project is open-source and free to use.
<img width="1715" height="989" alt="Screenshot 2025-09-21 132639" src="https://github.com/user-attachments/assets/d000faf0-7e07-49e5-ae7f-b66fb64d72ff" />
<img width="1630" height="876" alt="Screenshot 2025-09-21 132656" src="https://github.com/user-attachments/assets/8be40edb-ee6e-42ac-bcd3-953fc290f188" />
<img width="1682" height="898" alt="Screenshot 2025-09-21 132708" src="https://github.com/user-attachments/assets/980afb11-9931-4eec-86a9-d8a5286f21c4" />
<img width="995" height="853" alt="Screenshot 2025-09-21 132801" src="https://github.com/user-attachments/assets/779e78ca-6016-4a2c-aa49-9b36027b239a" />
<img width="918" height="834" alt="Screenshot 2025-09-21 132811" src="https://github.com/user-attachments/assets/31978cd8-6345-43c0-b82b-9bca03570456" />
<img width="761" height="826" alt="Screenshot 2025-09-21 133041" src="https://github.com/user-attachments/assets/d0a3b8c7-69e5-4c9d-849c-7b11afddc7b4" />





