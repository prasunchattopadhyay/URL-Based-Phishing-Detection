I develop this URL-based Phishing Detection Using Machine Learning. image image image image

Table of Content
Introduction
Installation
Directory Tree
Result
Conclusion
Introduction
The Internet has become an indispensable part of our life, However, It also has provided opportunities to anonymously perform malicious activities like Phishing. Phishers try to deceive their victims by social engineering or creating mockup websites to steal information such as account ID, username, password from individuals and organizations. Although many methods have been proposed to detect phishing websites, Phishers have evolved their methods to escape from these detection methods. One of the most successful methods for detecting these malicious activities is Machine Learning. This is because most Phishing attacks have some common characteristics which can be identified by machine learning methods. To see project click here.

Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt
Directory Tree
![image](https://github.com/BusamSumanjali/URL-Based-Phishing-Detection-using-meachine-Learning/assets/140227579/357e20a3-8488-451d-bffb-81a04c8256f9)

Technologies Used
Numpy
pandas
matplotlib.pyplot
sklearn
seaborn
flask
Result
Accuracy of various model used for URL detection

image

Conclusion
The final take away form this project is to explore various machine learning models, perform Exploratory Data Analysis on phishing dataset and understanding their features.
Creating this notebook helped me to learn a lot about the features affecting the models to detect whether URL is safe or not, also I came to know how to tuned model and how they affect the model performance.
The final conclusion on the Phishing dataset is that the some feature like "HTTTPS", "AnchorURL", "WebsiteTraffic" have more importance to classify URL is phishing URL or not.
Gradient Boosting Classifier correctly classify URL upto 94.01% respective classes and hence reduces the chance of malicious attachments.
