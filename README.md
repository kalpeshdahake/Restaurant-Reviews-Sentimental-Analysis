# **Restaurant-Reviews-Sentimental-Analysis**

<!DOCTYPE html>
<html>
<head>
  <title>Restaurant Reviews Analysis using NLP</title>
</head>
<body>

<h1>Restaurant Reviews Analysis using NLP (Natural Processing Language)</h1>

<h2>Problem Statement</h2>
<p>Performed analysis of customer reviews that are provided for a restaurant. The goal is to determine the accuracy of this data and classify reviews as true or false.</p>

<h2>Summary</h2>
<p>In this project, we analyze customer reviews for a restaurant. The objective is to classify reviews as positive/negative or like/unlike. We preprocess the data using Natural Language Processing (NLP) techniques to clean the text data and remove noise. The reviews are categorized as 1s (like) and 0s (unlike).</p>

<h2>Description of Process</h2>
<ol>
  <li>Import necessary libraries: NumPy, Pandas, Matplotlib, Seaborn, and OS.</li>
  <li>Define the directory path of the dataset.</li>
  <li>Display and verify the data using Pandas.</li>
  <li>Preprocess the data: remove punctuation, convert to lowercase, split into words, and apply stemming.</li>
  <li>Remove stopwords and keep impactful words (corpus).</li>
  <li>Create features using CountVectorizer with a limit of 1500 words.</li>
  <li>Train a Gaussian Naive Bayes model for classification.</li>
  <li>Train a Decision Tree classifier as an alternative approach.</li>
  <li>Evaluate model performance using confusion matrices and accuracy scores.</li>
</ol>

<h2>Conclusion</h2>
<p>This project demonstrates sentiment analysis for restaurant reviews using NLP and machine learning algorithms. While achieving a 73% accuracy, there's room for improvement by incorporating deep learning models like RNN or BERT.</p>

<h2>Improvement Needed</h2>
<p>Enhancements are needed to achieve higher accuracy. Consider using advanced Deep Learning algorithms like RNN or BERT, as well as machine learning algorithms such as Logistic Regression, Support Vector Machine, and Random Forest. Deep Learning models may provide better results.</p>

</body>
</html>
