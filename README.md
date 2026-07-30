# IMDB_Movie_Reviews--Vortex-Tech
Built an NLP sentiment classifier using TF-IDF, Logistic Regression, and Naive Bayes to analyze and predict review sentiments with 88%+ accuracy.

# Sentiment Analysis Model using NLP and Machine Learning
This project focuses on building a Natural Language Processing (NLP) based sentiment analysis model that classifies movie reviews as either **Positive** or **Negative**.
The objective of this project is to transform raw text data into meaningful numerical features and train machine learning models to automatically understand the sentiment behind user reviews.

## Project Workflow
- Collected and analyzed the IMDB Movie Reviews dataset containing 50,000 labeled reviews.
- Performed data inspection, handled duplicate records, and prepared the dataset for modeling.
- Cleaned text data by:
  - Converting text to lowercase
  - Removing HTML tags
  - Removing punctuation and special characters
  - Removing unnecessary spaces
- Converted text into numerical features using **TF-IDF Vectorization**.
- Trained and compared two machine learning classification models:
  - Logistic Regression
  - Multinomial Naive Bayes
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

## Model Performance
| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Logistic Regression | 88.53% | 88.74% |
| Multinomial Naive Bayes | 85.37% | 85.53% |
Logistic Regression achieved the best performance and was selected as the final sentiment classification model.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK / Regular Expressions
- TF-IDF Vectorization
- Machine Learning Classification Algorithms

## Prediction Examples
The trained model was tested on custom sentences and successfully predicted sentiments such as:

- Positive: "This movie was absolutely amazing. I loved every minute of it."
- Negative: "This was the worst movie I have ever watched. Completely boring."

## Limitations
The model uses TF-IDF based features, which focus mainly on word importance and frequency. Therefore, it may struggle with understanding sarcasm, complex emotions, or sentences where the context changes the meaning.

## Future Improvements
Possible improvements include:
- Using deep learning models such as LSTM or BERT for better contextual understanding.
- Expanding the dataset with more diverse text sources.
- Building a web application for real-time sentiment prediction.

## Conclusion
This project demonstrates a complete NLP machine learning pipeline, from text preprocessing and feature extraction to model training, evaluation, and prediction. It highlights how traditional machine learning techniques can effectively solve real-world text classification problems.
