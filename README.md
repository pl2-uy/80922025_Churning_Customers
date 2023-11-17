# 80922025_Churning_Customers
# Churn Prediction Model


## Project Description
This churn prediction model, developed using TensorFlow and Keras, is designed to help businesses forecast customer churn. Predicting churn is essential for businesses to take proactive measures in retaining existing customers, often more cost-effective than acquiring new ones.

## Project Structure

The project is organized into the following sections:

- **Data Preprocessing**: The dataset is loaded, checked for null values, and relevant columns are processed for better model compatibility. Irrelevant features are dropped, and categorical variables are encoded.

- **Exploratory Data Analysis (EDA)**: Both graphical and statistical EDA techniques are employed to understand the distribution and relationships within the dataset. Visualizations such as histograms, box plots, and count plots are used for a comprehensive analysis.

- **Feature Importance and Selection**: A Random Forest Classifier is employed to identify feature importance. Less relevant features are dropped to enhance model performance and interpretability.

- **Training the Model**: The dataset is split into training, validation, and testing sets. A neural network model is constructed using the Keras Functional API, and a Grid Search is performed for hyperparameter optimization.

- **Testing and Optimization**: The initial model is tested, and its performance is evaluated. A Grid Search is then conducted to optimize the model's hyperparameters. The final optimized model demonstrates improved accuracy and AUC score.

- **Deployment**: The optimized model is saved for future use, and a README.md file is created to guide users on how to utilize the model for predicting customer churn.


## Functionalities

### Data Collection
The model collects user input parameters, including tenure, internet service, contract, payment method, monthly charges, and total charges.

### Data Preprocessing
Input data undergoes preprocessing by encoding categorical features and scaling numerical features for optimal model compatibility.

### Prediction
The model utilizes preprocessed input data to make predictions, providing raw probabilities of the likelihood of customer churn.

### Thresholding
Raw probabilities are transformed into class labels using a user-defined threshold. The model outputs 'Yes' if the probability surpasses the threshold (indicating churn) and 'No' otherwise.

## How to Use

### Input Parameters
Use the sidebar to input parameters such as tenure, internet service, contract, payment method, monthly charges, and total charges.

### Prediction
Click the 'Predict' button to obtain the model's churn prediction.

### Thresholding
Customize the threshold for converting raw probabilities to class labels based on your desired confidence level.

### APPLICATION DEMO:
https://github.com/pl2-uy/80922025_Churning_Customers/assets/123755107/8370a3d3-2b69-4aaa-a2e8-a20bce3a36e6

