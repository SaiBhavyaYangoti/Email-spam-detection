# Email-spam-detection
This project implements an email spam detection system using logistic regression, based on a dataset downloaded from Kaggle. The dataset consists of labeled email messages, marked as either 'spam' or 'ham'. During preprocessing, null rows and unnecessary columns were removed. The text data was converted into numerical features using a TF-IDF vectorizer, and the labels were encoded, with 'spam' as 0 and 'ham' as 1. The dataset was then split into training and testing sets to train and evaluate the logistic regression model.

The model's performance was assessed using training and testing accuracy, and a confusion matrix was generated to visualize the classification results. The system achieved a satisfactory level of accuracy in distinguishing between spam and ham emails. This project demonstrates the effectiveness of using logistic regression combined with TF-IDF vectorization for email spam detection, showcasing a simple yet powerful approach to text classification.
