# SMS Spam Detection using Logistic Regression

## Project Overview

SMS Spam Detection is a Machine Learning classification project that identifies whether a text message is **Spam** or **Not Spam (Ham)** using Logistic Regression.

The project uses Natural Language Processing (NLP) techniques to convert text messages into numerical features and trains a Logistic Regression model to classify messages.

## Objectives

- Build a binary classification model using Logistic Regression.
- Clean and preprocess SMS message data.
- Convert text into numerical features using TF-IDF.
- Train and evaluate the machine learning model.
- Predict whether new messages are spam or legitimate.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Matplotlib
- Seaborn
- Joblib

## Dataset

**SMS Spam Collection Dataset**

Source: [Kaggle – SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

The dataset contains SMS messages labelled as:

- `ham` – Legitimate messages
- `spam` – Unwanted or promotional messages

## Project Workflow

1. Import required libraries.
2. Load the SMS dataset.
3. Perform data cleaning and preprocessing.
4. Remove duplicate and missing records.
5. Convert categorical labels into numerical values.
6. Separate features and target variables.
7. Split data into training and testing sets.
8. Apply TF-IDF Vectorization.
9. Train the Logistic Regression model.
10. Evaluate model performance.
11. Save the trained model using Joblib.
12. Test predictions using new messages.

## Machine Learning Algorithm

**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for binary classification.

In this project, it classifies SMS messages into two categories:

- 0 – Not Spam
- 1 – Spam

## Model Evaluation

The model is evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help measure the model's classification performance.

## Project Structure

```text
SMS-Spam-Detection/
│
├── spam_detection.py
├── spam.csv
├── spam_model.pkl
├── tfidf_vectorizer.pkl
└── README.md
```

## Installation and Setup

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project folder**

```bash
cd SMS-Spam-Detection
```

**3. Install dependencies**

```bash
pip install pandas scikit-learn matplotlib seaborn joblib
```

**4. Run the project**

```bash
python spam_detection.py
```

## Example Prediction

**Input:**

```text
Congratulations! You have won a free cash prize. Claim now!
```

**Expected output:**

```text
Prediction: SPAM
Spam Probability: Model-generated probability
```

The actual prediction and probability depend on the trained model.

## Future Improvements

- Develop a Streamlit web application.
- Add a user-friendly interface for message classification.
- Experiment with other classification algorithms.
- Improve text preprocessing.
- Compare model performance using different algorithms.

## Author

**Aditya Mungekar**

GitHub: [adityacodes6](https://github.com/adityacodes6)

## License

This project is intended for educational and learning purposes.