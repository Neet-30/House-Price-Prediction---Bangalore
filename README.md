## 🏠 Bangalore House Price Prediction

This project aims to **predict house prices in Bangalore** using a **machine learning model**.  
It uses a **Random Forest Regressor** trained on housing data and provides an **interactive Streamlit web app** for users to get real-time predictions based on parameters like **location, total area (sqft), number of bathrooms**, and **number of bedrooms (BHK)**.

## Overview
This project demonstrates a complete **end-to-end data science pipeline**:
- Data collection and preprocessing  
- Model training and evaluation  
- Deployment through a web-based user interface (Streamlit)  

The trained model predicts the price of houses in Bangalore based on user-input features.

>Some files are not available on GitHub due to the large file size. you can get it [HERE](https://huggingface.co/spaces/neet30/House-price-prediction/tree/main)

## Project Structure

The project consists of the following files and directories:

- `app.py`: The main script for the Streamlit web application.
- `Bengaluru_House_prediction.ipynb`: Jupyter notebook containing the data analysis and model training process.
- `random_forest_house_price_model.pkl`: Serialized machine learning model. `NOT AVAILABLE ON GITHUB DUE TO THE LARGE FILE SIZE.`
- `dataset.pkl`: Serialized dataset used for training the model.

## Dataset

The dataset used for this project is a comprehensive collection of housing data from Bangalore. It includes features such as location, total square footage, number of bathrooms, and number of bedrooms (BHK). The dataset is serialized and stored in `dataset.pkl`.

## Model

The machine learning model used in this project is a Random Forest Regressor. The model is trained on the dataset to predict house prices based on the input features. The trained model is serialized and stored in `random_forest_house_price_model.pkl`.

<img width="745" height="291" alt="image" src="https://github.com/user-attachments/assets/ab5f78df-fd0f-4ba9-8ef6-d3747f945488" />


<img width="1063" height="689" alt="image" src="https://github.com/user-attachments/assets/6802729d-f56e-45a4-89d0-f32b78e7ed1f" />

## Results

The web application allows users to input the location, total square footage, number of bathrooms, and number of bedrooms to get a predicted house price in Bangalore. The predicted price is displayed in lakhs.


<img width="1426" height="689" alt="image" src="https://github.com/user-attachments/assets/913c20c1-3e55-4841-a2f7-978a8291359f" />








