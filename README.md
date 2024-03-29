# Email-Spam-Detection-Project
Hello, this is the Email Spam Classifier Project using Python. I got this project under the internshp of Oasis Infobyte. I'm a Data Science Intern at Oasis Infobyte.
Spam mail detection is a common task in natural language processing (NLP) where the goal is to automatically determine whether a given piece of text (e.g., email, message) is SPAM or NOT.

1. We used scikit-learn library, which provides a range of machine learning algorithms and tools for text classification tasks.
 
2. We took the dataset 'Mail_CSV' that contains two columns: 'Message' and 'Category', where 'Message' represents the text of each message, and 'Category' indicates whether it is SPAM or NOT.

3. We load the dataset using pandas and split it into features (X) and labels (Y).

4. The data is split into training and testing sets using train_test_split from scikit-learn

5. We convert the text messages into numerical features using TfidVectorizer from scikit-learn

6. We train the spam classifier model using the Multinomial Naive Bayes algorithm, which is commonly used for text classification tasks.

7. At last we evaluate the model's performance by predicting labels for the testing set and comparing them to the actual labels.

8. We calculate the accuracy score and the confusion matrix to assess the model's performance.
