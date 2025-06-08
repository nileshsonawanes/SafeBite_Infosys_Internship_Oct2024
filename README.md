# SafeBite_Infosys_Internship_Oct2024

SafeBite: AI-Powered Allergen Detection in Food
SafeBite is an AI-powered application designed to help individuals with food allergies make informed decisions by identifying allergens in food products. By leveraging machine learning models, SafeBite provides real-time allergen detection, ensuring safer food choices and a better quality of life for people with food sensitivities.

Vision
Our vision is to create an inclusive world where individuals with food allergies can confidently make safe food choices. Through AI-powered allergen detection, SafeBite aims to empower people with the tools they need to avoid allergens and live healthier, more secure lives.

Mission
Our mission is to develop an intuitive, reliable, and efficient tool that allows users to identify potential allergens in food. By using advanced machine learning, SafeBite provides users with the ability to instantly detect allergens and make informed decisions.

Features
Real-Time Allergen Detection: Identify allergens in food products by analyzing ingredient data.
Instant Allergen Alerts: Receive notifications when a food item contains allergens, such as nuts, dairy, or gluten.
User-Friendly Interface: The app provides a clean, simple interface for easy interactions and quick allergen detection.
Customizable Allergen Preferences: Users can personalize the app to detect allergens based on their specific needs.
Multi-Ingredient Detection: SafeBite can process complex food items with multiple ingredients to detect allergens.
Real-Time Performance: The application offers quick responses for faster decision-making.
Technologies Used
Python: For backend development, machine learning model training, and data manipulation.
Pandas: For data processing, cleaning, and manipulation.
Scikit-learn: For implementing machine learning algorithms, including Random Forest for allergen detection.
Flask: A micro-framework for building the API and handling backend requests.
Streamlit: For front-end development, providing an interactive and user-friendly interface.
Joblib/Pickle: For saving and loading the trained machine learning models.

Datasets/
├── Allergen_Status_of_Food_Products.csv    # Raw food allergen data
├── preprocessed_data.csv                  # Cleaned and preprocessed dataset for model training

Model/
├── leave_one_out_encoder.pkl              # Encoder used during data preprocessing
├── random_forest_model.pkl               # Trained Random Forest model for allergen detection

Scripts/
├── AI_SafeBite_Data_Preprocessing.ipynb    # Data preprocessing and cleaning steps
├── AI_SafeBite_EDA.ipynb                  # Exploratory data analysis (EDA)
├── AI_SafeBite_Model_Testing.ipynb        # Model testing and evaluation
├── AI_SafeBite_Streamlit_Flask_App.py     # Main app code using Flask and Streamlit
├── AI_SafeBite_flask_api.py              # Flask API for allergen prediction
├── AI_SafeBite_Modeltraining.ipynb       # Model training and validation
├── AI_SafeBite.pdf                       # Final project documentation
