# Sentiment-Analysis

COMPANY: CODTECH IT SOLUTIONS

NAME: Vishal Anand

INTERN ID: CT06DG696

DOMAIN: Data Analytics

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

#DESCRIPTION:-

This repository contains my submission for Task-4 of the Codtech Internship, which focused on performing sentiment analysis using natural language processing (NLP) techniques. In this task, I worked on the Twitter US Airline Sentiment dataset to classify tweets into positive, negative, or neutral sentiments.

I began by loading the dataset and performing thorough data preprocessing. This included converting all tweets to lowercase to maintain consistency, removing unwanted characters and symbols such as punctuation marks and hyperlinks, and eliminating stopwords to retain only the meaningful words that contribute to sentiment. I further performed lemmatization to reduce words to their root form, which helped in reducing dimensionality and improving model understanding.

After cleaning the data, I transformed the textual data into numerical form using CountVectorizer. This step was crucial as machine learning models cannot process raw text data directly and require it to be converted into vectors. Once the feature extraction was done, I built a Multinomial Naive Bayes model, which is widely used for text classification problems due to its efficiency and simplicity.

I split the data into training and testing sets in an 80-20 ratio to evaluate the model effectively. After training, I evaluated the model using metrics such as accuracy score, confusion matrix, and a detailed classification report. The model achieved an accuracy of around 80%, indicating good performance in predicting sentiments from tweets. I also analysed the confusion matrix to understand where the model was performing well and where it was misclassifying tweets, which gave deeper insights into model behaviour.

The insights derived from this task showed that most tweets reflected negative sentiments towards airlines, indicating general customer dissatisfaction with services. This kind of analysis is crucial for airline companies as it helps them understand public opinion and improve their service quality based on data-driven decisions.

Overall, this task enhanced my understanding of natural language processing, especially in text preprocessing, feature extraction, and classification modelling. It strengthened my confidence in handling real-world textual datasets and analysing them effectively to derive meaningful business insights. I look forward to applying these skills in future projects involving customer reviews, brand monitoring, and other text-heavy data scenarios. This task was an excellent learning experience and a practical application of NLP in the domain of sentiment analysis.

