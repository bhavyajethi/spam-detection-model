**# Deepfake Audio Classification System**

This project is part of the **IGDTU Internship Program** and focuses on detecting deepfake audio using machine learning techniques. The system classifies audio samples as either **REAL** or **FAKE**, aiming to enhance the reliability of audio content in various applications.

**## Project Structure**

The project comprises the following components:
- **Audio Preprocessing**: Converts audio files into MFCC features for model input.
- **Model Architecture**:
  - Convolutional layers for feature extraction.
  - LSTM layers for temporal sequence modeling.
  - Fully connected layers for classification.
- **Evaluation Metrics**:
  - Confusion Matrix.
  - Receiver Operating Characteristic (ROC) Curve.
**## Dataset**

The dataset consists of two categories:

1. **REAL**: Authentic audio recordings.
2. **FAKE**: Deepfake audio samples.

Audio files are organized into respective directories for processing.

**## Getting Started**

**### Prerequisites**
Ensure the following are installed:

- Python 3.x
- Matplotlib
- Seaborn
- TensorFlow/Keras

## **Installation Steps**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/bhavyajethi/deepfake-audio-classification.git

2. **Navigate to the project directory**:
```bash
cd deepfake-audio-classification

3. **Install dependencies**:
```bash
pip install -r requirements.txt
