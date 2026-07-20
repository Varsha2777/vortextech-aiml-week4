\# Sentiment Analysis using IMDB Movie Reviews



\## Objective



The objective of this project is to build a Machine Learning model that can classify movie reviews as \*\*Positive\*\* or \*\*Negative\*\* using Natural Language Processing (NLP).



\---



\## Dataset



\- Dataset: IMDB Movie Reviews Dataset

\- Total Reviews: 50,000

\- Classes:

&#x20; - Positive

&#x20; - Negative



\---



\## Tools and Libraries Used



\- Python

\- Pandas

\- Regular Expressions (re)

\- Scikit-learn

\- TF-IDF Vectorizer

\- Logistic Regression

\- Jupyter Notebook



\---



\## Steps Performed



1\. Imported the required libraries.

2\. Loaded the IMDB Movie Reviews dataset.

3\. Explored the dataset using `head()`, `info()`, and `value\_counts()`.

4\. Cleaned the review text by:

&#x20;  - Converting text to lowercase

&#x20;  - Removing special characters

5\. Converted text into numerical features using \*\*TF-IDF Vectorization\*\*.

6\. Split the dataset into training and testing sets.

7\. Trained a \*\*Logistic Regression\*\* model.

8\. Predicted sentiments for the test dataset.

9\. Evaluated the model using:

&#x20;  - Accuracy

&#x20;  - F1 Score

&#x20;  - Confusion Matrix

10\. Tested the model on custom movie reviews.



\---



\## Model Performance



\- \*\*Accuracy:\*\* 89.28%

\- \*\*F1 Score:\*\* 89.48%



\---



\## Sample Predictions



| Review | Prediction |

|---------|------------|

| This movie is amazing and I loved it | Positive |

| This was the worst movie I have ever seen | Negative |

| The movie was okay not great not bad | Negative |



\---



\## Conclusion



The Logistic Regression model successfully classified IMDB movie reviews into positive and negative sentiments with high accuracy.



The project demonstrates how \*\*Natural Language Processing (NLP)\*\* and \*\*Machine Learning\*\* can be used to analyze customer opinions automatically. The model achieved strong performance and was also tested on custom reviews.



\---



\## Repository Contents



\- `Sentiment\_Analysis.ipynb`

\- `README.md`



