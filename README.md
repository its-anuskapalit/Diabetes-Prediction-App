# Diabetes Prediction App

This is a Streamlit-based web application that predicts whether a person has diabetes based on input features. The model used in this app is a Support Vector Machine (SVM) classifier trained on the Diabetes dataset.

## Features
- **User Input via Sidebar:** Users can input medical details such as pregnancies, glucose levels, blood pressure, BMI, and more.
- **Diabetes Prediction:** The app uses an SVM model to classify whether the person is diabetic or not.
- **Dataset Summary & Statistics:** Displays summary statistics of the dataset and the distribution of features by outcome.
- **Model Performance Metrics:** Shows training and testing accuracy of the model.

## Installation
### Prerequisites
Ensure you have Python installed on your system. Then, install the required dependencies:

```bash
pip install numpy pandas streamlit scikit-learn pillow
```

## Usage
1. Clone this repository:
```bash
git clone https://github.com/yourusername/diabetes-prediction-app.git
cd diabetes-prediction-app
```

2. Place the `diabetes.csv` dataset in the same directory.

3. Run the application:
```bash
streamlit run app.py
```

## Files
- `app.py`: Main Streamlit app
- `diabetes.csv`: Dataset used for training the model (ensure it is in the same directory)
- `img.jpeg`: Image displayed on the app

## Model Training
The model is an SVM classifier with a linear kernel. The dataset is standardized using `StandardScaler`, and the model is trained using an 80-20 train-test split.



