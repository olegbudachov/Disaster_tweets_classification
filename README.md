# Disaster_tweets_classification
Project outline:
Data Overview
Importing Libraries
Loading Data
EDA
Data Preprocessing
Models Architecture and Training
Models Evaluation
Tuning parameters for LSTM and GRU and analyzing results
Conclusion
References

Data Overview
add Codeadd Markdown
The Disaster Tweets Classification dataset is a widely used dataset in natural language processing (NLP) and machine learning for text classification tasks. This dataset is designed for the purpose of classifying tweets into two categories: those related to real disasters and those that are not. It's particularly useful for tasks such as sentiment analysis, disaster detection, and social media monitoring.

Here are some key characteristics of the Disaster Tweets Classification dataset:

The dataset comprises two main files: "train.csv" and "test.csv." In "train.csv," we find a total of 5 columns: "id," "keyword," "location," "text," and "target." Meanwhile, "test.csv" contains 4 columns: "id," "keyword," "location," and "text." train.csv consist of 7,613 rows, with the "id" column being well-balanced and containing no null values nad test.csv consist of 3,263 rows.

In "train.csv," it's evident that there's an imbalance in the distribution of the target variable. Specifically, there are 4,342 instances of non-disaster tweets (target = 0) and 3,271 instances of disaster-related tweets (target = 1). This class imbalance should be taken into account during the modeling and evaluation phases.

Overall, the dataset presents a valuable opportunity for text classification tasks, including the detection of real disasters in tweets.

The primary goal of this project is to determine which machine learning or deep learning model, among LSTM (Long Short-Term Memory), GRU (Gated Recurrent Unit), SVM (Support Vector Machine), Random Forest Classifier, and XGBoost Classifier, performs best for the task of classifying tweets into two categories: real disasters and non-disasters.We will use accuracy score to find the best fit.
