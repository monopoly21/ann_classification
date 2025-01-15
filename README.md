# Customer Churn Prediction Using ANN

This project focuses on predicting customer churn using an Artificial Neural Network (ANN). The model was developed using TensorFlow/Keras and deployed as a user-friendly web application via Streamlit. The solution leverages robust preprocessing pipelines to handle data efficiently, enabling businesses to identify and retain at-risk customers.

## Features
- **Customer Churn Prediction**: Predict whether a customer is likely to churn based on input features.
- **Interactive Web App**: User-friendly interface to input data and get instant predictions.
- **End-to-End Preprocessing**: Automated handling of missing values, normalization, and encoding of categorical variables.
- **Model Deployment**: Hosted on Streamlit for easy accessibility.

## Hosted Link
Access the application here: [ANN Churn Prediction Web App](https://annclassification-b3cgyjifdz2nfeurhl5vso.streamlit.app/)

## Technologies Used
- **TensorFlow/Keras**: For building and training the ANN model.
- **Streamlit**: For creating an interactive and accessible web application.
- **Pandas & NumPy**: For data preprocessing and feature engineering.
- **Scikit-learn**: For splitting data and preprocessing utilities.

## Project Overview
1. **Data Preprocessing**:
   - Handled missing values and performed feature scaling.
   - Encoded categorical variables using one-hot encoding.
2. **Model Development**:
   - Designed a feedforward neural network with multiple dense layers.
   - Optimized the model using backpropagation and various hyperparameters.
   - Evaluated performance using metrics like accuracy and recall.
3. **Deployment**:
   - Deployed the trained model as a Streamlit app for real-time predictions.

## Installation
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/krishnaik06/ANN-CLassification-Churn.git

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the Streamlit app:
   ```bash
   streamlit run app.py

## Usage
   - Open the hosted app or run it locally.
   - Enter customer details in the input fields.
   - Click on the "Predict" button to get the churn prediction.

## Future Enhancements
   - Incorporate additional features to improve prediction accuracy.
   - Add a feature to upload bulk data for batch predictions.
   - Enhance the user interface for better user experience.
## License
   - This project is licensed under the MIT License.
