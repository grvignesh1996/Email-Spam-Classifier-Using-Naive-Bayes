# Email-Spam-Classifier-Using-Naive-Bayes

* This is a basic spam classifier using Naive Bayes algorithm
* We have a bunch of emails classified as ['Spam'](https://github.com/Surya-Murali/Email-Spam-Classifier-Using-Naive-Bayes/tree/master/emails/spam)
and a bunch of emails classified as ['ham'](https://github.com/Surya-Murali/Email-Spam-Classifier-Using-Naive-Bayes/tree/master/emails/ham)
(not spam). 
* We read and store the emails in a dataframe and then parse them to get the count of each word in a specific email using CountVectorizer
* This information is used to train the model and its prediction is then tested with a sample input

Python Libraries used: pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn

The output is a classification of spam / ham and is found [here.](https://github.com/Surya-Murali/Email-Spam-Classifier-Using-Naive-Bayes/blob/master/SpamClassifierOutput.txt)
