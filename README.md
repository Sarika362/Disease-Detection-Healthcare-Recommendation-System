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

- **`app.py`**: Main Flask application file with route handling and template rendering.
- **`model.py`**: Contains functions for disease prediction and retrieving disease details.
- **`dataset_mini_prj.csv`**: Dataset with symptoms and corresponding diseases.
- **`templates/index.html`**: HTML template for the web interface.
- **`static/css/styles.css`**: CSS styles for the application.

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

- Developed by [Sarika M N](https://github.com/Sarika362), [Shashank B R](https://github.com/Shashankx22)
- Initial Dataset source: [Dataset Source](https://www.kaggle.com/datasets/pasindueranga/disease-prediction-based-on-symptoms)

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve this project!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Sarika362/Disease-Detection-Healthcare-Recommendation-System/blob/main/License) file for details.

---

Thank you for checking out the Disease Detection and Healthcare Recommendation project! 🙌
