# Iris_Flower_Classification

  Overview

    This repository contains a Streamlit web application that predicts the type of iris flower based on user input features. Using a Random Forest Classifier and        the Iris dataset from scikit-learn, the app takes user-defined measurements for sepal length, sepal width, petal length, and petal width and classifies the iris 
    species as one of three types: Setosa, Versicolor, or Virginica.


Features

	•	User Input via Sliders: Allows users to input iris flower measurements.
	•	Real-time Prediction: Predicts the species of iris flower based on the user’s input.
	•	Prediction Probability: Displays the probability of each class to provide insights into the model’s confidence.
	•	Interactive UI: Built with Streamlit for a responsive and easy-to-use interface.


Technologies Used

	•	Python 3.x: Core programming language.
	•	Streamlit: Framework for creating the interactive web interface.
	•	Pandas: Data manipulation and handling for the user inputs.
	•	Scikit-learn: For the machine learning model (Random Forest Classifier) and the Iris dataset.


Prerequisites

  Ensure you have Python 3.x, Streamlit, Pandas, and Scikit-learn installed. You can install them via pip:

      pip install pandas
      pip install scikit-learn
      pip install streamlit

Installation

1.	Clone this repository:

        git clone https://github.com/Shivesh-22/iris-flower-classification.git
    	
2.	Navigate to the project directory:

        cd iris-flower-classification


Running the App

To run the Streamlit app, use the following command:

    streamlit run main.py
    
  This will open the app in your web browser, where you can adjust the input sliders and see real-time predictions.


How to Use

	1.	Open the app and navigate to the sidebar.
	2.	Adjust the sliders for Sepal Length, Sepal Width, Petal Length, and Petal Width to specify flower measurements.
	3.	View the prediction and probability on the main page to see the classified iris species and the confidence level.

Code Structure

	•	main.py: Main script containing the app logic, user input parameters, model training, and prediction.


Model Details

	•	Random Forest Classifier: A pre-trained Random Forest model is used to classify the iris flower species based on input features. The model is trained on the standard Iris dataset from scikit-learn.
