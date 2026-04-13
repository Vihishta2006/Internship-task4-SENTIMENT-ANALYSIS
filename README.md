# Internship-task4-SENTIMENT-ANALYSIS

*COMPANY NAME*: CODETECH IT SOLUTIONS

*NAME*: VISHISHTA H E

*INTERN ID*: CTIS5381

*DOMAIN*: DATA ANALYTICS

*DURATION*: 12 WEEKS (3 MONTHS)

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*

This task focuses on Sentiment Analysis, which is a technique used to understand the emotions or opinions expressed in text data. In simple words, it helps to identify whether a piece of text (like a review or comment) is positive, negative, or neutral. This is very useful in understanding customer feedback, opinions, and overall satisfaction.

To perform this task, the main programming language used is Python. Python is widely used in text analysis and natural language processing because it is simple, powerful, and has many useful libraries.
One of the most important tools used in this task is NLTK. NLTK is a popular library used for working with human language data. It provides various tools to process text, including tokenization, classification, and sentiment analysis. In this task, a specific model called VADER (Valence Aware Dictionary and sEntiment Reasoner) is used through NLTK. This model is specially designed to analyze sentiments in short texts like reviews and social media comments.

Another library used is Pandas, which helps in loading and managing the dataset. The dataset used here contains reviews, and Pandas makes it easy to read the CSV file and store it in a structured format like a table.

For visualization, Matplotlib is used. This library helps in creating graphs and charts so that the results can be easily understood. In this task, a bar chart is created to show the number of positive and negative reviews.
The editor or platform used for this task can be Visual Studio Code, which is a popular tool for writing and running Python code. It provides a clean interface and supports many extensions. Another option is Jupyter Notebook, which is especially useful for beginners because it allows you to run code step-by-step and see outputs instantly.

The task begins by loading the dataset that contains text reviews. After loading the data, the sentiment analysis model is initialized. Before using the model, the required dataset (vader_lexicon) is downloaded, which contains words and their sentiment scores.

Next, each review in the dataset is analyzed using the VADER model. The model assigns a score to each review, which represents the sentiment of the text. This score is called the “compound score” and ranges from -1 to +1. A positive score indicates positive sentiment, a negative score indicates negative sentiment, and a score close to zero indicates neutral sentiment.

Based on this score, each review is labeled as Positive, Negative, or Neutral using a simple function. This makes it easy to categorize all the reviews.
After labeling the sentiments, the results are visualized using a bar chart. The chart shows how many reviews are positive, negative, or neutral. This helps in quickly understanding the overall sentiment of the dataset.

This task is very useful in many real-world applications. For example, companies use sentiment analysis to understand customer feedback about their products or services. It is also used in social media monitoring to analyze public opinion about brands, movies, or events. Businesses can use this information to improve their products, services, and customer experience.

In simple words, this task shows how computers can understand human emotions from text. It converts unstructured text data into meaningful insights. Instead of manually reading thousands of reviews, this method can quickly analyze and summarize the overall sentiment.
Overall, this task is an important step in learning Natural Language Processing (NLP). It helps in understanding how text data can be processed and analyzed using machine learning tools. It also shows how results can be visualized to make them easy to understand for everyone.

*OUTPUT

<img width="640" height="480" alt="Image" src="https://github.com/user-attachments/assets/a618e5e6-281a-4752-9fa7-4aeff71ea610" />
