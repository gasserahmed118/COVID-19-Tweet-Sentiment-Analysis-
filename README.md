🧠 COVID-19 Tweet Sentiment Analysis using TF-IDF & Random Forest

📌 Overview

This project performs sentiment analysis on COVID-19 related tweets using both handcrafted textual features and TF-IDF vectorization.
The goal is to compare traditional text statistics with TF-IDF representations when applied to binary and multi-class sentiment classification tasks.

The project demonstrates a complete NLP workflow including:
1. Data exploration
2. Feature engineering
3. Text vectorization
4. Model training
5. Performance evaluation

🎯 Objectives

   1. Analyze public sentiment during the COVID-19 pandemic
   2. Compare feature-based models vs TF-IDF models
   3. Perform binary and multi-class sentiment classification
   4. Visualize performance using confusion matrices

📂 Dataset
    Name: COVID-19 Tweets Dataset
    Format: CSV
    Key Columns:
      1. OriginalTweet – Tweet text
      2. Sentiment – Sentiment label

🏗 Project Structure
 📦 covid19-sentiment-analysis
 ┣ 📜 README.md
 ┣ 📓 TFIDF_Sentiment_Analysis.ipynb
 ┣ 📁 data
 ┃ ┗ 📄 Corona.csv
 ┣ 📁 results
 ┃ ┣ 📊 confusion_matrix_binary.png
 ┃ ┣ 📊 confusion_matrix_multiclass.png
 ┗ 📁 models


🔎 Exploratory Data Analysis (EDA)
The dataset is explored using:
   1. data.info()
   2. data.describe()
   3. Sentiment distribution
   4. Sample tweets inspection

Additional engineered features include:
  1. Tweet length
  2. Sentence length
  3. Number of digits
  4. Special characters count
  5. Number of links

🧩 Feature Engineering
   1️⃣ Handcrafted Text Features
      1. Total characters
      2. Word count
      3. Numeric characters
      4. Special symbols
      5. URLs count

   2️⃣ TF-IDF Vectorization
      1. Converts tweets into numerical vectors
      2. Captures word importance across the corpus
      3. High-dimensional sparse representation


🤖 Models Used
Random Forest Classifier


📊 Evaluation Metrics
   Each model is evaluated using:
     1. Precision
     2. Recall
     3. F1-Score
     4. Confusion Matrix
     5. Confusion Matrices

   Confusion matrices are plotted for:
      1. Binary sentiment classification
      2. Multi-class sentiment classification
These visualizations help analyze class-wise performance and misclassification patterns.


📈 Performance Summary
   1. TF-IDF significantly outperforms handcrafted features
   2. Binary classification achieves higher accuracy than multi-class
   3. Neutral and extreme sentiments are harder to distinguish
   4. Random Forest handles sparse TF-IDF features effectively

🛠 Technologies Used
   1. Python
   2. Pandas
   3. NumPy
   4. Scikit-learn
   5. Matplotlib
   6. Jupyter Notebook


👤 Author

Gasser Ahmed
Machine Learning & NLP Enthusiast
