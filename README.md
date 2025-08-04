# Natural-Language-Processing-with-Generative-AI

**Project Title:**

Sentiment-Driven Stock Market Prediction Using NLP and Word Embeddings

**Project Objective:**

To build an AI-driven system that analyzes news articles related to a NASDAQ-listed company, identifies their sentiment (positive, negative, or neutral), and summarizes this information weekly to improve stock movement predictions—thereby enabling better investment decisions.

**Project Approach:**

1.) Data Collection & Preprocessing:

* Historical stock news and stock prices were compiled.
* Preprocessing steps included text cleaning, handling missing values, and sentiment labeling.

2.) Exploratory Data Analysis (EDA):

* Performed univariate and bivariate analysis on stock attributes like volume, open, close, high, and low prices.
* Detected class imbalance in sentiment labels (neutral being the most frequent).

3.) Text Embedding Techniques:

Two embedding techniques were used:

* Word2Vec: To capture semantic relationships between words.
* GloVe: As a comparative embedding method.

4.) Model Building:

* Random Forest classifiers were trained on both Word2Vec and GloVe embeddings.
* Models were fine-tuned using Grid Search.
* Weekly sentiment aggregation was done to align better with real market reaction times.

5.) Model Evaluation & Selection:

* Word2Vec + Random Forest (GridSearch) provided the best accuracy and generalization.
* Selected as the final production model.

**Outcome:**

1.) Developed a sentiment analysis system that can predict stock movement with reasonable accuracy using financial news.

2.) Confirmed that weekly aggregated sentiment improves prediction performance over daily scores.

3.) Validated that Word2Vec embeddings are more effective than GloVe in this context.

4.) Identified actionable recommendations for model deployment and expansion:

* Use model in real-time prediction pipelines.
* Incorporate more diverse news sources.
* Integrate sentiment outputs with trading indicators like RSI or MACD.
* Enhance explainability using SHAP or LIME.
