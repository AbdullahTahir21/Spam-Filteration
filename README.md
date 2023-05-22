# Spam-Filteration
Emails have become crucial part of everyone’s day to day life but they contain sensitive information that could be stolen through malicious/spam emails. So we have designed this software to detect ham (not harmful, needed) emails and spam (harmful, malicious) emails.

SPAM FILTERATION
This is a Python program that implements a spam filter using the Naive Bayes algorithm. It provides a graphical user interface (GUI) for users to train the model, test emails for spam classification, and display a bar chart of email classes.

Prerequisites
Firstly make sure you have the following libraries installed:

csv
tkinter
sklearn
pandas
matplotlib


Run the spam_filter.py file to start the program.

The GUI window will open. You can perform the following actions:

Train: Click the "Train" button to preprocess the data, train the spam filter model using the Naive Bayes algorithm, and display the accuracy of the model.

Check: Enter an email in the provided input field and click the "Check" button to test the email for spam classification. A message box will display whether the email is classified as spam or ham (not spam). Additionally, the email will be appended to the "spam.csv" file with the corresponding label.

Bar Chart: Click the "Bar Chart" button to display a bar chart showing the distribution of email classes (spam and ham) in the dataset.

Customize the code as needed. You can modify the data preprocessing steps, feature extraction techniques, or machine learning algorithm to improve the spam filter's performance.

Dataset
The spam filter uses the "spam.csv" dataset for training and testing. Make sure the dataset file is in the same directory as the code files. The dataset should contain two columns: "class" and "email". The "class" column contains the labels (spam or ham), and the "email" column contains the email text.
