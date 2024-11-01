# Resume Screening App

This project implements a resume screening application that uses a K-Nearest Neighbors (KNN) model to identify the profession of resumes. The application preprocesses text data from resumes, applies machine learning technique, and provides an intuitive web interface for users to upload and classify resumes.

## Features

- Identifies the profession of resumes using a KNN model
- Text data preprocessing, including cleaning and normalization
- Label encoding for categorical features
- TF-IDF vectorization for text representation
- User-friendly interface built with Streamlit
- Deployed on a server for easy access

## How It Works

1. **Data Preprocessing**: The application cleans the text data from resumes by removing unnecessary characters and normalizing the text. Categorical features are transformed using label encoding.

2. **Vectorization**: The cleaned text data is converted into numerical format using TF-IDF vectorization, allowing the KNN model to effectively analyze the data.

3. **Model Training**: A KNN model is trained on a labeled dataset of resumes to classify the profession based on the text input.

4. **Web Interface**: Users can upload resumes through a Streamlit web interface. The application processes the uploaded file and returns the predicted profession.

## Requirements

To run this project, ensure you have the following libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `streamlit`
