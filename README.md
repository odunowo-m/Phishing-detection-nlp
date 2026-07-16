Phishing Detection and Response System Using NLP

 Overview
A machine learning-based phishing email detection system built in Python 
using Natural Language Processing techniques as part of a BSc Cybersecurity 
and Digital Forensics dissertation at the University of Sunderland.

System Performance
- Logistic Regression accuracy: 95.6%
- Phishing recall: 0.99
- False negative rate: 1.2%
- Test set: 1,950 emails

How It Works
1. Emails are preprocessed using tokenisation, stop-word removal and lowercasing
2. TF-IDF vectorisation converts text into numerical features (max 5,000 features)
3. Two models were trained and compared — Multinomial Naïve Bayes and Logistic Regression
4. Logistic Regression was selected as the final model based on superior performance
5. Automated response recommendations are generated following classification

Technologies Used
- Python
- Scikit-learn
- NLTK
- Pandas
- Matplotlib
- Google Colab

Datasets
- Kaggle Phishing Email Dataset
- SMS Spam Collection Dataset

How to Run
1. Open Google Colab at colab.research.google.com
2. Upload the .ipynb notebook file
3. Upload both CSV dataset files
4. Click Runtime → Run all
5. All results and graphs will be generated automatically

Results
The system successfully classifies phishing emails with high accuracy and 
generates automated response recommendations to guide user decision making
