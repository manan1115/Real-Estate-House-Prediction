## Real-Estate-House-Price-Prediction-Website
![front ](https://github.com/user-attachments/assets/0590e4fb-8f8a-4746-a501-ae548d650d30)

This project is a comprehensive step-by-step guide to building a Real Estate Price Prediction web application. The primary goal is to predict housing prices in Bangalore using machine learning models. The project is divided into three major components:

**1)Model Building**:
Using the Bangalore home prices dataset from Kaggle, we will build a predictive model with Linear Regression from scikit-learn. During this process, we will explore essential data science techniques like:
+ Data loading and preprocessing
+ Handling missing values and outlier detection/removal
+ Feature engineering and dimensionality reduction
+ Hyperparameter tuning using GridSearchCV
+ Evaluating the model with K-Fold Cross Validation

**2)Python Flask Server**: 
Once the model is trained, we will create a Python Flask server that can serve the trained model for making real-time predictions via HTTP requests.

**3)Web Interface**: 
The final component is a responsive web application built using HTML, CSS, and JavaScript. This UI allows users to input relevant features like square footage, number of bedrooms, etc., and get a real-time prediction from the Flask server.

## Features of the Project
**Data Science Techniques Covered**:
+ Data Cleaning using Pandas
+ Data Visualization with Matplotlib
+ Model building and evaluation with scikit-learn
+ Dimensionality reduction and feature selection
+ Hyperparameter tuning with GridSearchCV
+ Outlier detection and handling
+ K-Fold Cross Validation for model performance assessment

**Web Application**:
- A user-friendly web interface where users can enter house attributes like area, number of bedrooms, etc.
- The website makes AJAX requests to the Flask server for predictions in real-time.
- Simple yet functional front-end built using HTML, CSS, and JavaScript.

**Technology Stack**:
+ Python: Core programming language for model development and server-side scripting.
+ Numpy and Pandas: For efficient data manipulation and cleaning.
+ Matplotlib: For data visualization and exploratory analysis.
+ Scikit-learn: Machine learning library for building the prediction model.
+ Flask: Lightweight web framework to serve the trained model via HTTP requests.
+ HTML/CSS/JavaScript: For front-end development of the user interface.
+ IDE/Tools: Jupyter Notebook, Visual Studio Code, and PyCharm for development.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/manan1115/Real-Estate-House-Price-Prediction.git

2. **Install Dependencies**: Ensure you have Python 3.x installed. Install the necessary Python packages by running
   ```bash
   pip install -r requirements.txt

4. **Train the Model**: Run the Jupyter notebook for data preprocessing and model building
   ```bash
   jupyter BengaluruHousePredicition.ipynb

6. **Start Flask Server** : After training the model, save it and run the Flask server
   ```bash
   python app.py
8. **Run the web interface**: Open index.html in your web browser to interact with the website.

## Dataset
The dataset used in this project is the Bangalore Home Prices dataset, available on Kaggle. It includes features such as the square footage of the house, the number of bedrooms, and the location any many more features.

## Future Improvements
+ Implement additional machine learning models like Random Forest or XGBoost for better prediction accuracy.
+ Deploy the web application using cloud platforms like Heroku or AWS for a fully functional online service.
+ Add more features like property location, proximity to amenities, and crime rates to improve the prediction model.
