# NLP-DepressionClassifier

## About
Our goal in this project is to build a deep learning classifier that detects depression and suicidal text. We implemented static convolutional neural network, bidirectional lstm and lstm with attention layer. We also used SVM as a baseline as it is a common machine learning approach to text classification.

## Dataset
We scraped a total of 1.9 million rows from the following subreddits. We assumed that users posting on r/depression are depressed whille users posting on r/SuicideWatch are suicidal.

Subreddits:
* [https://www.reddit.com/r/happy/](r/happy)
* [https://www.reddit.com/r/CasualConversation](r/CasualConversation)
* [https://www.reddit.com/r/depression/](r/depression)
* [https://www.reddit.com/r/SuicideWatch/](r/SuicideWatch)

To get the dataset, please run the scrape subreddit script in the scrape subreddit directory. Follow the example on how the scrape object can be used.

* Link: https://github.com/ElmoSamudra/NLP-DepressionClassifier/tree/master/scrape_subreddit

Clean the data can be done in our preprocessing subreddit script.

* Preprocessing: https://github.com/ElmoSamudra/NLP-DepressionClassifier/blob/master/preprocessing_visualization/preprocess_subreddit.ipynb

* Train test split: https://github.com/ElmoSamudra/NLP-DepressionClassifier/blob/master/preprocessing_visualization/train_test_split.ipynb

## Report
Here is the link for our report: https://github.com/ElmoSamudra/NLP-DepressionClassifier/blob/master/final_report.pdf

## Contributors
* Nathanael Luira Yoewono
* Jonathan Aland Prasetiyo
* Shawn Elmo Samudra
