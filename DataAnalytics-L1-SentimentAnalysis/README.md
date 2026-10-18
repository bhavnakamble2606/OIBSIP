# Sentiment Analysis on Twitter Data

## Project Overview
This project performs sentiment analysis on tweets and classifies them into three categories: Negative, Neutral, and Positive.

## Objectives
- Explore and understand the sentiment dataset.
- Clean and preprocess tweet text.
- Convert text into numerical features using TF-IDF.
- Train and compare two machine learning models.
- Evaluate model performance using classification metrics and confusion matrices.
- Visualize sentiment distribution and frequent words using WordClouds.

## Technologies Used
- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

## Dataset
The project uses a Twitter sentiment dataset containing tweet text and sentiment labels.

The dataset was cleaned by removing missing and duplicate text entries. The resulting dataset contains 27,480 rows and two main columns: text and sentiment.

## Data Preprocessing
- Converted text to lowercase.
- Removed URLs, punctuation, and non-alphabetic characters.
- Tokenized text.
- Removed English stopwords.
- Applied TF-IDF vectorization with a maximum of 5,000 features.

## Models and Results

| Model | Accuracy |
|---|---:|
| Naive Bayes | 63.16% |
| Logistic Regression | 68.27% |

Logistic Regression achieved better accuracy on the test dataset.

## Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The project also includes a sentiment distribution bar chart, three WordCloud visualizations, and an analysis of five misclassified tweets.

## Conclusion
The project demonstrates how machine learning can classify tweet sentiment. Sentiment analysis can support social media monitoring, customer feedback analysis, and product review analysis. Informal language and context-dependent expressions remain challenges.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries: pandas, nltk, scikit-learn, matplotlib, seaborn, and wordcloud.
3. Place the dataset file in the project folder.
4. Open `sentiment_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

## Author
Oasis Infobyte Data Analytics Internship – Task 4
