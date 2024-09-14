# TrueScan

This project aims to classify news articles as **Fake** or **Real** using Machine Learning techniques. The project uses the Kaggle Fake News dataset, containing both fake and true news articles.

## Dataset
- **Source**: Kaggle Fake News Dataset.
- The dataset consists of two CSV files: `Fake.csv` (containing fake news) and `True.csv` (containing true news).

## Steps
1. **Data Loading**: Load the `True.csv` and `Fake.csv` datasets.
2. **Data Preprocessing**:
   - Label data (0 = Fake, 1 = True).
   - Merge and shuffle the data.
   - Clean the text using tokenization and removing stopwords.
3. **Feature Extraction**: Convert text data to numeric form using TF-IDF (Term Frequency-Inverse Document Frequency).
4. **Model Building**:
   - Train a Logistic Regression classifier to classify news as Fake or True.
5. **Model Evaluation**:
   - Use accuracy, confusion matrix, and classification report to evaluate the model.
6. **Prediction**: Classify new news articles using the trained model.

## Libraries Used
- `pandas`
- `sklearn`
- `nltk`
- `re`

