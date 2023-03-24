Customer Churn Prediction with Machine Learning and Django
This is a web application that uses machine learning to predict customer churn for a business. The application is built with Django, a high-level Python web framework, and utilizes various machine learning algorithms to make predictions.

Installation and Usage
To run this application, you will need to have Python 3 installed on your machine. You can download it from the official Python website: https://www.python.org/downloads/

Once Python is installed, you can clone this repository to your local machine using Git:
git clone https://github.com/hariharancse11/customer-churn-prediction.git


![IP](https://user-images.githubusercontent.com/33338812/227437961-7772f7f9-c95b-4acf-87c7-37a64c95f05b.png)
![op](https://user-images.githubusercontent.com/33338812/227437969-7b71b541-f200-4a1d-ab0a-dcaec02bc7e3.png)

You should now be able to access the application by navigating to http://localhost:8000 in your web browser.

Overview
The application allows the user to upload a dataset containing customer information, and then select various machine learning algorithms to make predictions about which customers are most likely to churn.

The following algorithms are currently supported:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
Once the user has made their selections, the application will train the selected algorithms on the provided dataset, and display the resulting predictions in an easy-to-read table.

To run the server:
python manage.py runserver
