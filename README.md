# Project Title: Spam Mail Prediction

This project leverages Logistic Regression to analyze email content and distinguish between legitimate emails (ham) and spam.  Text data from emails is transformed into numerical features using TF-IDF vectorization, enabling the model to learn the key characteristics that differentiate spam from ham emails. It utilizes the the mail_data.csv dataset and performs the following steps:

1. Data Preparation: Emails are loaded, preprocessed, and labeled accordingly (spam or ham).
2. Feature Engineering: TF-IDF vectorization extracts informative features from email text, capturing the importance of words within an email relative to the entire email corpus.
3. Model Training: The Logistic Regression model is trained on the prepared data, learning the patterns that distinguish spam from ham emails.
4. Evaluation: The model's performance is assessed on unseen data to gauge its effectiveness in generalizing to new emails.
5. Prediction: See how the trained model can classify a new email as spam or ham, showcasing its practical application.

By implementing this project, I gained a practical understanding of:

- Logistic Regression for binary classification tasks.
- TF-IDF vectorization for text feature extraction.
- Building a spam email filtering system using machine learning.
