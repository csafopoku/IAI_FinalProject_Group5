# IAI_FinalProject_Group5
Tweet Classifier
Project Overview:
This project is a Flask-based web application designed to classify tweets into various categories of cyberbullying. It utilizes a machine learning model built with TensorFlow and Keras for text classification. The user interface allows users to input a tweet URL, after which the application processes and classifies the tweet content, displaying results that indicate potential cyberbullying.
Features:
Web interface for easy interaction and classification of tweets.
Utilizes an LSTM (Long Short-Term Memory) model for accurate text classification.
Real-time tweet fetching and classification using Tweepy and TensorFlow.
Prerequisites:
Before setting up the project, ensure you have the following:
Python 3.x installed.
Flask web framework.
TensorFlow for running the LSTM model.
Tweepy for Twitter API interaction.
Joblib for model loading.

Local Setup:
Clone the Repository: Start by cloning this repository to your local machine.
Install Dependencies: Navigate to the project directory and install the required Python packages.
Configure Twitter API Credentials: You will need to obtain Twitter API credentials and set them as environment variables or directly within the application script.
Start the Flask Application: Run the Flask application using the command:

Usage Instructions
Our project is hosted on a local server that provides a beautiful interface that gets the user interested from the get-go.

After running flask in your terminal, command click on the link that is provided 
Copy and paste the URL of the tweet you want to classify in the provided input field.
Click the "Classify" button to submit the tweet for classification.
The classification results, including the category of cyberbullying (if any), will be displayed on the page.



