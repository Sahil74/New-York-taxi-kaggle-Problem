# New York Taxi Fare Prediction
New York City Taxi Fare Prediction Can you predict a rider's taxi fare?

## Project Overview

- The New York Taxi Fare Prediction project aims to predict taxi fares using historical taxi trip data. This project demonstrates data preprocessing, feature engineering, and model building to predict taxi fares from various features such as pickup and dropoff locations, date, and time. The project utilizes machine learning techniques, including regression and deep learning, to achieve accurate predictions.

## Dataset

- The dataset used for this project is obtained from Kaggle. It contains information about taxi trips, including:
Pickup and dropoff locations (latitude and longitude)
Pickup and dropoff times
Fare amount
- The dataset is loaded and preprocessed to prepare it for analysis and modeling.

## Project Structure

#### Data Preprocessing
- Load dataset and adjust pickup times for timezone.
- Extract date and time features, and create a binary mornight feature.
- Drop unnecessary columns.

#### Feature Engineering
- Calculate distance between pickup and dropoff points using the Haversine formula.
- Prepare feature matrix X and target vector y.

#### Model Building
- Analyze feature importance using Extra Trees Regressor.
- Split data into training and testing sets.
- Train an Artificial Neural Network (ANN) using TensorFlow/Keras.

#### Evaluation
- Predict taxi fares on the test set and evaluate using metrics such as MSE, MAE, R2, and RMSE.
- Save the processed dataset.


## Key Results

- Feature Importance: The feature importance plot shows the top features affecting fare prediction.
- Model Performance: The ANN model achieved:
- Mean Squared Error (MSE): 12.51
- Mean Absolute Error (MAE): 2.07
- R2 Score: 0.78
- Root Mean Squared Error (RMSE): 3.54

## Evolution

- The project evolves from basic data preprocessing to advanced modeling techniques, including feature engineering and deep learning. The ANN model improves accuracy and provides insights into the key features influencing taxi fare predictions.
