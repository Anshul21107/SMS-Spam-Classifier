# SMS Spam Classifier

SMS Spam Classifier is a machine learning project that classifies SMS messages as either spam or not spam (ham). This project uses natural language processing (NLP) techniques and a supervised machine learning model to make predictions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anshul21107/sms-spam-classifier.git

2. Navigate to the project directory:

   ```bash
   cd sms-spam-classifier

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

## Usage

1. Train the SMS Spam Classifier model:

   ```bash
   python train.py
2. Use the trained model to classify SMS messages:

   ```bash
   from sms_spam_classifier import SMSClassifier
   # Initialize the classifier
   classifier = SMSClassifier()

   # Classify an SMS message
   message = "Congratulations, you've won a free iPhone!"
   result = classifier.classify(message)
   print(result)

## Data
The SMS Spam Classifier uses a labeled dataset of SMS messages. The dataset is with name spam.csv. It consists of two columns: text and label, where text contains the SMS messages, and label contains the corresponding labels (spam or ham).

## Model
The project uses a machine learning model for text classification. The model architecture and hyperparameters can be found in the model.pkl file.

## Evaluation
The performance of the SMS Spam Classifier is evaluated using metrics such as accuracy, precision, recall, and F1-score. You can find the evaluation results in the SMS_Spam_detection.ipynb Jupyter Notebook.


