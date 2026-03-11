# Fake News Detection Using Machine Learning

## Project Overview
This project focuses on building a machine learning model to automatically classify news articles as **Fake News** or **Real News** using **Natural Language Processing (NLP)** techniques.

With the rapid spread of misinformation on the internet, automated systems for detecting fake news have become increasingly important. This project demonstrates how machine learning can be used to analyze textual data and identify misleading news articles.

---

## Dataset
The dataset used in this project is the **Fake and Real News Dataset** obtained from Kaggle.

Dataset characteristics:
- Around **44,000 news articles**
- Two categories:
  - Fake news
  - Real news
- Each record contains:
  - Title
  - News article text
  - Subject
  - Date

Dataset Source: Kaggle Fake and Real News Dataset

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Matplotlib
- Seaborn

---

## Methodology

The following steps were performed to build the fake news detection system:

1. **Data Loading**
   - Loaded fake and real news datasets using Pandas.

2. **Data Preprocessing**
   - Removed unnecessary columns
   - Cleaned text using regular expressions
   - Converted text to lowercase
   - Removed punctuation and extra spaces

3. **Feature Extraction**
   - Used **TF-IDF Vectorization** to convert text data into numerical form.

4. **Model Training**
   - Logistic Regression
   - Naive Bayes
   - Random Forest

5. **Model Evaluation**
   - Accuracy score
   - Confusion Matrix
   - Model comparison graph

---
## Project Workflow

The workflow of the fake news detection system follows these steps:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Text Feature Extraction using TF-IDF
4. Training Machine Learning Models
5. Model Evaluation and Comparison
6. Visualization of Results

This pipeline demonstrates a complete machine learning workflow from raw data processing to model evaluation.
---

## Model Performance

| Model | Accuracy |
|------|------|
| Logistic Regression | 98.8% |
| Naive Bayes | 94.3% |
| Random Forest | 98.9% |

The Random Forest and Logistic Regression models achieved the highest accuracy.

---

## Visualizations

### Confusion Matrix

![Confusion Matrix]
<br>
<img src="https://github.com/Ashwini07-cmd/Fake-News-Detection-Using-Machine-Learning/blob/731c8944b93a214eae5f51e78d7d8ec4e454a565/Confusion%20Matrix.png" alt="Image Description" width="600">
<br>
The confusion matrix shows the performance of the classification model and highlights correct and incorrect predictions.

---

### Model Comparison Graph

![Model Comparison]
<br>
<img src="https://github.com/Ashwini07-cmd/Fake-News-Detection-Using-Machine-Learning/blob/731c8944b93a214eae5f51e78d7d8ec4e454a565/Machine%20Learning%20Model%20Comparison.png" alt="Image Description" width="600">
<br>
This graph compares the accuracy of different machine learning models used in the project.

---

## Results

The results demonstrate that machine learning models combined with NLP techniques can effectively detect fake news articles with high accuracy.

The Random Forest and Logistic Regression models achieved the best performance with an accuracy close to **99%**.

---

## Conclusion

This project shows how Natural Language Processing and Machine Learning can be used to detect misinformation in news articles. By applying TF-IDF vectorization and multiple classification algorithms, the model successfully identifies fake news with high accuracy.

---
## Future Improvements

Possible improvements for this project include:

- Using Deep Learning models such as LSTM or BERT for better text understanding.
- Deploying the model as a web application for real-time fake news detection.
- Expanding the dataset with more diverse news sources.
- Performing advanced NLP techniques such as word embeddings.

These improvements could further enhance the performance and applicability of the fake news detection system.
---

## Author

Ashwini Fatkar  
Bachelor of Computer Science Student
