# SENTIMENT-ANALYSIS
COMPANY:CODTECH IT SOLUTIONS

NAME: Nandini Shankar Waghmare

INTERN ID:CTIS3494

DOMAIN:Data Analytics

DURATION:16 Weeks

MENTOR:NEELA SANTOSH

q1:In this task, I performed sentiment analysis on a small dataset using Python in a Jupyter Notebook.
First, I imported the required libraries such as Pandas for handling data, TextBlob for sentiment analysis, and Matplotlib for visualization.
Next, I created a dataset that contains different text reviews. These reviews include positive, negative, and neutral opinions about a product or service. I converted this data into a DataFrame using Pandas and displayed it using .head().
After that, I defined a function called get_sentiment() to analyze each review. This function uses TextBlob to calculate the sentiment polarity of the text. Based on the polarity value:
If it is greater than 0 → Positive
If it is less than 0 → Negative
If it is 0 → Neutral
Then, I applied this function to the review column and created a new column called sentiment, which shows the result for each review.
Next, I counted how many reviews fall into each category (Positive, Negative, Neutral) using value_counts().
Finally, I created a bar chart using Matplotlib to visualize the sentiment results. The chart shows the number of reviews in each sentiment category, making it easy to understand the overall opinion of users.
Overall, this task demonstrates how to analyze text data, classify sentiments, and visualize the results in a simple and clear way

q2:First, I imported important libraries such as Pandas, NumPy, Matplotlib, TextBlob, and some tools from Scikit-learn.
Next, I created a dataset of text reviews and converted it into a DataFrame. I cleaned the data by removing missing values and converting all text to lowercase for better processing.
Then, I defined a function to find the sentiment of each review using TextBlob. Based on the polarity score, each review was labeled as Positive, Negative, or Neutral. This created a new column called sentiment.
After that, I prepared the data for machine learning. I used CountVectorizer to convert text into numerical form so that the model can understand it. Then, I split the data into training and testing sets using train_test_split().
Next, I trained a model using the Multinomial Naive Bayes algorithm. This model learns from the training data and predicts the sentiment of new data.
After training, I tested the model using the test data and calculated the accuracy score. I also printed a classification report to check performance.
Finally, I created a bar chart using Matplotlib to show how many reviews are Positive, Negative, and Neutral.
