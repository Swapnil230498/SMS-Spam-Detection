# SMS-Spam-Detection
Spam vs. Ham

# Overview

SMS Spam Detection is a self-initiated machine learning project that focuses on identifying whether a given text message is spam (unsolicited and potentially harmful) or ham (legitimate and non-spam). The project addresses the challenge of classifying SMS messages into these two categories, contributing to enhanced user safety and experience.

# Methodology

    Handling Class Imbalance: The first step in the project involved addressing class imbalance to ensure a fair representation of spam and ham messages, mitigating biases in the model.

    Feature Engineering: To improve classification accuracy, new features were introduced. The project incorporated indicators for currency and numerical content within the text, providing additional insights for effective spam detection.

    Data Preprocessing: The raw text data underwent several preprocessing steps to enhance model performance. Special characters, punctuations, and numbers were removed from the data, facilitating further analysis. Additionally, stopwords were eliminated, and lemmatization/stemming was applied to normalize words.

    Text Vectorization: The preprocessed text dataset was transformed into a vectorized format using Term Frequency-Inverse Document Frequency (TF-IDF) representation from sklearn. This conversion prepared the textual data for training the machine learning models.

    Model Training: The dataset was divided into an 80% training set and the remaining for testing. The project employed two machine learning models, namely Naive Bayes Classifier and Decision Tree, to learn patterns and characteristics of spam and ham messages.

    Evaluation and Results: A classification report was generated to assess the performance of the trained models. The report offered insights into precision, recall, F1-score, and accuracy, critical metrics to evaluate the effectiveness of the SMS Spam Detection system.

# Dataset

The SMS Spam Detection project was built using a self-created labeled dataset comprising SMS messages classified as either spam or ham. This personalized dataset served as the foundation for training, evaluating, and refining the machine learning models.
Usage

# To utilize the SMS Spam Detection model:

    Clone this repository to your local machine.
    Run the SMS Spam Detection app or script to classify SMS messages as spam or ham.

Please note that this project is a personal endeavor, and its primary purpose is educational and exploratory. As a self-initiated project, I welcome feedback and suggestions from fellow developers and machine learning enthusiasts.
Acknowledgments

I express my gratitude to the online community and various learning resources that have contributed to my knowledge and understanding, enabling me to embark on this SMS Spam Detection project. The journey of building this project has been a valuable learning experience.

Thank you for exploring my SMS Spam Detection project. Together, we endeavor to create a more secure and efficient text messaging experience for users.
