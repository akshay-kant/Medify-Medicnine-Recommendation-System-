# Medicine Recommendation System

## Overview
The Medicine Recommendation System is a machine learning-based application designed to recommend medicines based on user inputs. In addition to medicine recommendations, the system also suggests precautions, workout routines, and dietary advice to support user health and well-being.

## Features
- **Medicine Recommendation**: Based on symptoms and other relevant inputs, the system recommends appropriate medicines.
- **Precautions**: Provides important precautions that users should follow while taking the recommended medicines.
- **Workout Suggestions**: Offers workout routines tailored to the user's health condition.
- **Dietary Advice**: Suggests diet plans that complement the recommended medicines and help in quicker recovery.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**: 
  - Various recommendation algorithms were explored.
  - **Support Vector Classifier (SVC)** was selected as the optimal model for making predictions.
- **Database**: SQLite (or any other DB you might have used)

## Machine Learning Model
- **Algorithms Explored**: The system evaluates multiple recommendation algorithms, including:
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Random Forest
  - Naive Bayes
  - **Support Vector Classifier (SVC)** (selected model)
- **Selected Model**: 
  - The SVC model was chosen for its accuracy and performance in predicting the most suitable medicine based on the input features.
  - The model is trained on a dataset containing features such as symptoms, patient history, and other relevant medical data.

## Flask Application
- The application uses the Flask framework for both frontend and backend integration.
- **Endpoints**:
  - `/` - Home page where users can input their symptoms.
  - `/recommend` - Processes the input and provides medicine recommendations along with precautions, workout suggestions, and diet plans.


