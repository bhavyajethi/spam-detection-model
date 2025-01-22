Email/SMS Spam Classifier
This project is a machine learning-based application designed to classify messages as Spam or Not Spam. It uses natural language processing (NLP) techniques to preprocess text data and a trained machine learning model to make predictions. The application is deployed using Streamlit, making it interactive and user-friendly.

Features
Text Preprocessing:

Converts messages to lowercase.
Removes stopwords, punctuation, and non-alphanumeric characters.
Applies stemming to reduce words to their base forms.
Machine Learning Model:

Trained on a dataset of labeled SMS messages using a vectorizer and classification model.
Uses TF-IDF Vectorization for feature extraction.
Supports prediction of spam or non-spam messages.
Streamlit Web Application:

User-friendly interface for entering text and obtaining predictions.
Displays results in real-time as either Spam or Not Spam.
Tech Stack
Programming Languages:

Python
Libraries and Tools:

Streamlit: For building the web application.
NLTK: For text preprocessing (stopwords, tokenization, stemming).
Scikit-learn: For machine learning (vectorization and modeling).
Pickle: For model and vectorizer serialization.
Model:

Pre-trained classification model stored as a .pkl file (model.pkl).
TF-IDF vectorizer stored as a .pkl file (vectorizer.pkl).
Prerequisites
Ensure the following are installed:

Python 3.x
Streamlit
NLTK
Scikit-learn
Installation Steps
Clone the repository:
git clone https://github.com/bhavyajethi/deepfake-audio-classification.git
Navigate to the project directory:
cd email-sms-spam-classifier
Install dependencies:
pip install -r requirements.txt
Run the Streamlit Application:
streamlit run app.py
