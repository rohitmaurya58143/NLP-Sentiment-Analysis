# NLP Sentiment Analysis

## About Project

This is a simple NLP project which is used to find the sentiment of a review. The model classifies the review into three categories:

* Positive
* Negative
* Neutral

I used text preprocessing, TF-IDF and Logistic Regression for this project.

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn
* Jupyter Notebook

## How It Works

1. Load the review dataset.
2. Check for missing values.
3. Clean the review text.
4. Remove numbers, special characters and stopwords.
5. Apply stemming using Porter Stemmer.
6. Convert the text into numerical values using TF-IDF.
7. Split the data into training and testing data.
8. Train the Logistic Regression model.
9. Check the accuracy of the model.
10. Enter a new review and predict its sentiment.

## Model Used

**Logistic Regression**

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

The model accuracy is calculated using `accuracy_score`.

## Example

```text
Enter your experience/review: This product is very good

Predicted Sentiment: Positive
```

## Project Files

```text
NLP-Sentiment-Analysis/
│
├── reviews_dataset.csv
├── sentiment_analysis.ipynb
└── README.md
```

## How to Run

Install the required libraries:

```bash
pip install pandas nltk scikit-learn
```

Download NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

Then open the Jupyter Notebook and run the cells one by one.

## Objective

The main purpose of this project is to use NLP and Machine Learning to understand the sentiment of text reviews.

## Author

Rohit Maurya
