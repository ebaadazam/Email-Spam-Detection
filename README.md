# CodeClause-Spam-Classifier-Project
Hello, this is the Spam Classifier Project using Python. I got this project under the internshp of CodeClause. I'm an Artificial Intelligence Intern at CodeClause.
Spam classification is a common task in natural language processing (NLP) where the goal is to automatically determine whether a given piece of text (e.g., email, message) is SPAM or NOT.
We used scikit-learn library, which provides a range of machine learning algorithms and tools for text classification tasks.
We took the dataset 'Mail_CSV' that contains two columns: 'Message' and 'Category', where 'Message' represents the text of each message, and 'Category' indicates whether it is SPAM or NOT.
We load the dataset using pandas and split it into features (X) and labels (Y).
The data is split into training and testing sets using train_test_split from scikit-learn
We convert the text messages into numerical features using TfidVectorizer from scikit-learn
We train the spam classifier model using the Multinomial Naive Bayes algorithm, which is commonly used for text classification tasks.
At last we evaluate the model's performance by predicting labels for the testing set and comparing them to the actual labels. We calculate the accuracy score and the confusion matrix to assess the model's performance.
