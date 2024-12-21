# **Email/SMS Spam Classifier**

This project is a machine learning-based application designed to classify messages as **Spam** or **Not Spam**. 
It uses natural language processing (NLP) techniques to preprocess text data and a trained machine learning model to make predictions. The application is deployed using **Streamlit**, making it interactive and user-friendly.

---

## **Features**

1. **Text Preprocessing**:
   - Converts messages to lowercase.
   - Removes stopwords, punctuation, and non-alphanumeric characters.
   - Applies stemming to reduce words to their base forms.

2. **Machine Learning Model**:
   - Trained on a dataset of labeled SMS messages using a vectorizer and classification model.
   - Uses **TF-IDF Vectorization** for feature extraction.
   - Supports prediction of spam or non-spam messages.

3. **Streamlit Web Application**:
   - User-friendly interface for entering text and obtaining predictions.
   - Displays results in real-time as either **Spam** or **Not Spam**.

---

## **Tech Stack**

1. **Programming Languages**: 
   - Python

2. **Libraries and Tools**:
   - **Streamlit**: For building the web application.
   - **NLTK**: For text preprocessing (stopwords, tokenization, stemming).
   - **Scikit-learn**: For machine learning (vectorization and modeling).
   - **Pickle**: For model and vectorizer serialization.

3. **Model**:
   - Pre-trained classification model stored as a `.pkl` file (`model.pkl`).
   - TF-IDF vectorizer stored as a `.pkl` file (`vectorizer.pkl`).

---

## **Prerequisites**

Ensure the following are installed:

- Python 3.x
- Streamlit
- NLTK
- Scikit-learn

## **Installation Steps**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/bhavyajethi/deepfake-audio-classification.git

2. **Navigate to the project directory**:  
   ```bash
   cd email-sms-spam-classifier

3. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   
4. **Run the Streamlit Application**:  
   ```bash
   streamlit run app.py





