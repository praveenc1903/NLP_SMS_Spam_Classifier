<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; max-width: 800px; margin: auto;">

  <h1>📩 NLP SMS Spam Classifier</h1>
  <p>
    A machine learning project that classifies SMS messages as <strong>spam</strong> or <strong>ham (not spam)</strong> using <strong>Natural Language Processing (NLP)</strong> techniques.
  </p>

  <h2>🔍 Project Overview</h2>
  <p>This project demonstrates a basic text classification task using NLP. It involves:</p>
  <ul>
    <li>Preprocessing text data (tokenization, stopword removal, stemming, etc.)</li>
    <li>Visualizing patterns in spam and ham messages</li>
    <li>Training a classification model to identify spam messages</li>
  </ul>

  <h2>🧰 Libraries Used</h2>
  <ul>
    <li><code>numpy</code>, <code>pandas</code> – data manipulation</li>
    <li><code>matplotlib</code>, <code>seaborn</code> – data visualization</li>
    <li><code>nltk</code> – text preprocessing</li>
    <li><code>string</code> – punctuation handling</li>
    <li><code>wordcloud</code> – visualizing word frequency</li>
    <li><code>google.colab</code> – for Colab-specific file access</li>
  </ul>

  <h2>📁 Dataset</h2>
  <p>
    The dataset contains labeled SMS messages marked as <strong>spam</strong> or <strong>ham</strong>. A sample format:
  </p>
  <pre>
label   | message
--------|---------------------------------
ham     | I'm going to be home soon and I...
spam    | WINNER!! As a valued network cus...
  </pre>
  <p>
    Common dataset: <a href="https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection" target="_blank">UCI SMS Spam Collection</a>
  </p>

  <h2>⚙️ Preprocessing Steps</h2>
  <ul>
    <li>Lowercasing</li>
    <li>Removing punctuation</li>
    <li>Removing stopwords</li>
    <li>Stemming (Porter Stemmer)</li>
    <li>Tokenization</li>
  </ul>

  <h2>📊 Exploratory Data Analysis</h2>
  <ul>
    <li>WordClouds for spam vs. ham</li>
    <li>Frequency plots</li>
    <li>Message length distribution</li>
  </ul>

## 🧠 Machine Learning Algorithms Used

The following classifiers were tested and compared in this project:

- **Linear Models:**
  - Logistic Regression
- **Support Vector Machine:**
  - SVC
- **Naive Bayes Variants:**
  - MultinomialNB
  - BernoulliNB
  - GaussianNB
- **Tree-based Models:**
  - Decision Tree
  - Random Forest
  - Extra Trees Classifier
- **Instance-based Learning:**
  - K-Nearest Neighbors (KNN)
- **Ensemble Methods:**
  - Bagging Classifier
  - AdaBoost
  - Gradient Boosting
  - XGBoost

### 📏 Evaluation Metrics
- `accuracy_score`
- `precision_score`
- `confusion_matrix`


  <h2>🚀 How to Run</h2>
<ol>
  <li>Clone the repository:<br>
    <code>git clone https://github.com/your-username/NLP_SMS_Spam_Classifier.git</code>
  </li>
  <li>Open the project in <strong>Google Colab</strong> or your local <strong>Jupyter Notebook</strong>.</li>
  <li>Install the required libraries (if not already installed):<br>
    <code>pip install nltk wordcloud seaborn</code>
  </li>
  <li>Download the necessary NLTK data packages:
    <pre><code>import nltk
nltk.download('stopwords')
nltk.download('punkt')</code></pre>
  </li>
  <li>Run the notebook cells one by one and follow the outputs.</li>
</ol>



  <h2>👨‍💻 Author</h2>
  <p>
    <a href="https://github.com/praveenc1903" target="_blank">Praveen C</a>
  </p>

</body>
</html>
