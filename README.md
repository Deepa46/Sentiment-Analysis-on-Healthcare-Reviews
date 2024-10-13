## Sentiment Analysis on Healthcare Reviews
This project focuses on classifying healthcare reviews into Positive, Neutral, or Negative sentiment categories.The process involves data preprocessing, feature extraction, model training, and sentiment analysis to understand common themes in patient feedback.
### Requirements
* Python 3.7+
* Required libraries: `numpy`, `pandas`, `scikit-learn`, `nltk`, `matplotlib`
### Dataset
The dataset comprises healthcare reviews with the following features:
* **Review_Text:** The content of the healthcare review.
* **Rating:** Numerical rating(1-5).
* **Sentiment:**  Label derived from the rating (1 for positive, 0 for neutral, -1 for negative).
### Approach
**Data Preprocessing:**
* Removed missing values.
* Cleaned the review text through standard NLP techniques such as lowercasing, removing punctuation, stopwords removal, and lemmatization.
* Transformed the processed text using TF-IDF vectorization for feature extraction.
  
**Model Training and Tuning:**
* Applied several machine learning algorithms, including K-Nearest Neighbors, Random Forest, Logistic Regression, and Multinomial Naive Bayes.
* Used hyperparameter tuning to optimize the models.

**Sentiment Analysis and Key Insights:**
* Identified frequently mentioned words and themes.
* Analyzed key terms across sentiment categories to understand patient experiences.

