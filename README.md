# BANGLORE HOME PRICES

### Overview

This project aims to predict home prices in Bangalore using data science techniques. It involves building a machine learning model utilizing the Bangalore home prices dataset sourced from Kaggle.com. The model is constructed using Scikit-learn library and Linear Regression algorithm. Additionally, a Python Flask server is developed to serve HTTP requests, allowing users to input home square footage, number of bedrooms, etc., and retrieve predicted prices. The user interface is designed using HTML, CSS, and JavaScript.

### Technologies and Tools Used

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Scikit-learn for model building
Jupyter Notebook and Visual Studio as IDE
Python Flask for HTTP server
HTML/CSS/JavaScript for UI
AWS instance for deployment

### Project Workflow

**1. Data Collection:**
    Obtain the Bangalore home prices dataset from Kaggle.com.

**2. Data Cleaning:**
    Load the dataset using Pandas.
    Clean the data by handling missing values and duplicates.

**3. Outlier Detection and Removal:**
    Identify outliers in the dataset using visualization techniques.
    Remove outliers to improve model accuracy.

**4. Feature Engineering:**
    Extract relevant features from the dataset.
    Transform categorical variables into numerical format using techniques like one-hot encoding.

**5. Dimensionality Reduction:**
    Apply techniques like Principal Component Analysis (PCA) to reduce the dimensionality of the dataset while preserving important information.

**6. Model Building:**
    Utilize Scikit-learn to build a Linear Regression model.
    Implement GridSearchCV for hyperparameter tuning to optimize model performance.

**7. Evaluation:**
    Assess model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
    Employ K-fold Cross Validation to validate the model's robustness.

**8. Server Development:**
    Develop a Python Flask server to handle HTTP requests.
    Integrate the trained model into the Flask server to serve predictions.

**9. User Interface Design:**
    Design a web-based user interface using HTML, CSS, and JavaScript.
    Allow users to input home features and retrieve predicted prices.

**10. Deployment:**
    Deploy the project on an AWS instance to make it accessible over the internet.

### Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the Flask server.
4. Access the web interface via a browser.
5. Input the desired home features.
6. Retrieve the predicted price.

### Future Improvements

Incorporate advanced machine learning algorithms for improved prediction accuracy.
Enhance the user interface for better usability and aesthetics.
Implement additional features such as location-based predictions or historical price trends.
