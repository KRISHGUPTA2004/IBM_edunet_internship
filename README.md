#💼 Employee Salary Prediction Web App

📌 Project Overview

This project is a web-based application that predicts whether an employee earns more than 50K or less than or equal to 50K annually based on demographic and professional information. Built using Streamlit, the model is deployed using Ngrok inside Google Colab, allowing for real-time predictions directly from the browser.

Users can enter individual data through the sidebar for instant predictions, or upload a CSV file for batch classification. The model is trained on the UCI Adult dataset.

📊 Model Description

Algorithm Used: GradientBoostingClassifier

Best Performing Model: GradientBoosting with accuracy: 0.8582

Evaluation Metric: Accuracy Score, Confusion Matrix, Classification Report

📈 Model Performance

✅ Accuracy: 85.82% on test data

📉 Balanced precision and recall observed

📊 Evaluated on key metrics using classification_report

🌐 Live Demo

You can access the live, deployed web application here:

🔗 Live App via Ngrok

⚠️ Note: As this is a temporary ngrok tunnel, the link may expire. For a fresh deployment, use the Colab file provided in the repository.

📝 How to Use

Clone the repository or open the provided Google Colab link.

Run app.py using Streamlit inside Colab.

Ngrok will create a live link — use it to access the app.

Use the sidebar to input employee details or upload a CSV file.

📂 Files in Repository

app.py: Main Streamlit app

best_model.pkl: Trained and serialized model using joblib

README.md: Documentation for the project

notebook.ipynb: Optional – EDA and model training pipeline (if included)

👨‍💻 Author

Developed by Krish Gupta

Feel free to ⭐ star or fork the repo!
