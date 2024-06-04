# Email_Spam_classification
Implemented Logistic Regression, a powerful supervised learning algorithm, to train the model on the preprocessed email data and accurately classify incoming emails as spam or non-spam

## Email Spam Classification with Logistic Regression in Django

This project tackles the issue of spam filtering using Logistic Regression within the Django framework. Here's a breakdown:

* **Machine Learning Model:** Logistic Regression is employed to analyze email features. It learns to distinguish spam emails from legitimate ones based on these features. Common features include:
    * Presence of certain keywords or phrases commonly found in spam.
    * Sender and recipient information (e.g., unknown sender address).
    * Presence of ALL CAPS text or excessive punctuation marks.
    * Capitalization ratio (higher ratio might indicate spam).
    * Presence of URLs or attachments.

* **Django Integration:** The trained Logistic Regression model is integrated into your Django application. Incoming emails are preprocessed to extract relevant features. These features are then fed into the model, which predicts the probability of an email being spam.

* **Spam Filtering:** Based on the predicted probability (often compared to a threshold like 0.5), emails are classified as spam or legitimate. Spam emails can be directed to a separate folder or even deleted automatically.

**Benefits:**

* **Improved Inbox Management:** Reduces unwanted emails cluttering your inbox.
* **Enhanced Security:** Protects users from phishing attempts and malicious attachments.
* **Scalability:** The model can be continuously improved by incorporating new data and adjusting features.

**Overall, this project demonstrates the combination of machine learning and Django to build a practical email spam filtering system.**

