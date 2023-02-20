# Sentiment Analysis Of Amazon Food Reviews
This project performs sentiment analysis on Amazon food reviews. It uses the Pandas, NumPy, Matplotlib, Seaborn, and NLTK libraries in Python. The project is summarized as follows:

- Loading Datasets: The code loads the dataset and prints its shape and the first two rows to verify its accuracy.

- Data preprocessing: This step includes tokenization, lowercase conversion, stop words removal, stemming and lemmatization, and removing punctuation and special characters. The code uses the NLTK library for tokenization, stop words removal, and stemming. The string and regular expression libraries are used for removing punctuation and special characters.

- Word frequency distribution: This section presents the frequency distribution of the words in the Amazon food reviews using the NLTK library.

- EDA: The code generates a bar plot showing the count of reviews by score.

- Word Cloud: The code creates a word cloud of the most frequent words in the reviews using the WordCloud library.

- Bar Plot: The code generates a bar plot of the frequency distribution using Matplotlib.

- Sentiment Distribution: This section uses the Vader Sentiment Intensity Analyzer to generate sentiment scores for the reviews. It creates a scatter plot of the positive and negative sentiment scores and a bar plot of the sentiment scores by review score.

- Top Products: The code finds the top products with the most reviews.

- Transformers Pipeline: The code performs sentiment analysis on a sample review using the Transformers library.

Overall, this code performs sentiment analysis on Amazon food reviews using various natural language processing techniques and libraries in Python.
