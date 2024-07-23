# SpamCLassification
It will focus on both: building a machine learning model for spam SMS message classification, then create an API for the model, using Flask, the Python micro framework for building web applications.This API allows us to utilize the predictive capabilities through HTTP requests. Let’s get started!

ML Model Building
The data is a collection of SMS messages tagged as spam or ham that can be found here. First, we will use this dataset to build a prediction model that will accurately classify which texts are spam.

Naive Bayes classifiers are a popular statistical technique of e-mail filtering. They typically use bag of words features to identify spam e-mail. Therefore, We’ll build a simple message classifier using Naive Bayes theorem.
Turning the Spam Message Classifier into a Web Application
Having prepared the code for classifying SMS messages in the previous section, we will develop a web application that consists of a simple web page with a form field that lets us enter a message. After submitting the message to the web application, it will render it on a new page which gives us a result of spam or not spam.

First, we create a folder for this project called SMS-Message-Spam-Detector , this is the directory tree inside the folder. We will explain each file.
