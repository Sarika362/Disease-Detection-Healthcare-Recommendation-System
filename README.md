# Disease-Detection-Healthcare-Recommendation-System
![image](https://github.com/user-attachments/assets/48043517-1944-4f38-8dd9-6d3e40bcbe6f)

# 🌟 Disease Detection and Healthcare Recommendation 🌟

Welcome to the Disease Detection and Healthcare Recommendation project! This web application, built with Flask, predicts diseases based on symptoms and provides healthcare recommendations.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- Flask
- pandas
- scikit-learn
- joblib

###  🛠️Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sarika362/Disease-Detection-Healthcare-Recommendation-System.git
   cd Disease-Detection-Healthcare-Recommendation-System

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Running the Application

To start the application, run:
```bash
python app.py
```

The app will be accessible at http://localhost:5000/.

## 🛠️ Usage

1. Enter your symptoms in the input box (comma-separated).
2. Click on the search icon or press Enter.
3. The app predicts the disease based on the provided symptoms.
4. View details such as the predicted disease, cure, doctor, risk level, and probability.

## 📂 Project Structure

SE_ML_Model

<pre>
static<br />
&nbsp;&nbsp;&nbsp;&nbsp;└── css<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── styles.css 🎨<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── bg.gif 🌟<br />
templates<br />
&nbsp;&nbsp;&nbsp;&nbsp;└── index.html 🖥️<br />
└── app.py 🔧<br />
└── model.py 🤖<br />
└── dataset.csv 📊
</pre>


- **static/**: Contains static files like CSS and background images.
  - **css/**: Contains stylesheets and background images.
    - `styles.css` 🎨
    - `bg.gif` 🌟
- **templates/**: Contains HTML templates for the web pages.
  - `index.html` 🖥️
- **app.py**: The main Flask application file. 🔧
- **model.py**: Contains the machine learning model and related functions. 🤖
- **dataset.csv**: The dataset used to train the machine learning model. 📊


## Features 🌟

- **Symptom Input**: Users can enter symptoms in a text box and submit them for analysis. 📝
- **Disease Prediction**: The application uses a trained machine learning model to predict possible diseases based on the entered symptoms. 🔍
- **Health Care Recommendations**: Provides recommended treatments, doctors, and risk levels associated with the predicted diseases. 💊🩺
- **Probability of Prediction**: Displays the probability of the predicted disease. 📉
- **Responsive Design**: The user interface is designed to be responsive and user-friendly. 📱

## 🔍 Example Usage

Here’s how to use the core functions of the project:

```python
# Example input
input_symptoms = "fever, cough, sore throat"

# Predict the disease
disease, probability = predict_disease(input_symptoms)
print(f"Predicted Disease: {disease}, Probability: {probability}")

# Get details of the predicted disease
disease_details = get_disease_details(disease)
print(f"Disease Details: {disease_details}")

# Evaluate the model
evaluate_model()
```

## 📊 Model Evaluation

The model is evaluated using accuracy and classification report metrics. Ensure you have the `dataset_mini_prj.csv` file for evaluation.

## 💡 Credits

- Developed by [Sarika M N](https://github.com/Sarika362)
- Initial Dataset source: [Dataset Source](https://www.kaggle.com/datasets/pasindueranga/disease-prediction-based-on-symptoms)

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve this project!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Sarika362/Disease-Detection-Healthcare-Recommendation-System/blob/main/License) file for details.

---

Thank you for checking out the Disease Detection and Healthcare Recommendation project! 🙌
