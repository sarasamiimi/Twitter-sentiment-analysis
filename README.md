
A machine-learning pipeline for classifying the sentiment of Twitter posts into positive, negative, and neutral categories.
The project includes data cleaning, TF-IDF feature extraction, supervised learning models, performance evaluation, and a Streamlit interface for real-time text prediction.



Features 

• End-to-end ML pipeline
From raw text to fully trained sentiment classifier.

• Classical ML with strong baselines
Uses TF-IDF vectorization and multiple ML algorithms (e.g., Logistic Regression, Naive Bayes, SVM).

• Real-time prediction interface
Built using Streamlit for interactive sentiment analysis.

• Clean, interpretable model
Outputs probabilities and class labels.

• Well-structured and reproducible
Notebook includes full preprocessing, training, hyperparameter tuning, and evaluation.




Project Structure 

├── app.py # Streamlit app for live predictions ├── data/ # Dataset (train/test) ├── model.pkl # Serialized trained model ├── vectorizer.pkl # TF-IDF feature extractor ├── Sentiment_analysis.ipynb # Training + evaluation notebook └── requirements.txt # Dependencies 




Methodology 

Text Cleaning
Tokenization, lowercasing, punctuation/stopword removal, normalization

Feature Extraction
TF-IDF vectorizer with unigrams + bigrams

Model Training
Evaluated several algorithms and saved the best one

Evaluation
Accuracy, Precision, Recall, F1-score, Confusion Matrix

Deployment
Streamlit interface for user-friendly interaction



How to Run Install dependencies: 

pip install -r requirements.txt 

Launch the Streamlit app: 

streamlit run app.py 

Type any sentence, and the model returns the sentiment label and confidence.


Example Predictions 

• “I love this!” → Positive
• “This is the worst thing ever.” → Negative
• “It’s okay, nothing special.” → Neutral


Why This Project Matters 

Social media text is noisy, unstructured, and full of linguistic variation.
This project demonstrates strong skills in:

• Natural Language Processing (NLP)
• Classical machine learning pipelines
• Streamlit deployment
• Text preprocessing techniques
• Understanding model evaluation
