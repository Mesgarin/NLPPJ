# NLPPJ
Final Project for Text Analysis and NLP Project: Advancing Emotion Detection from Text

**Attention ( in the proposal I don't mention ChatGPT but as an extra thing that I think maybe interesting I added it to my project and explained it. Best regards )**

Proposal of Text Analysis and Natural Language Processing Course
Project Title: Advancing Emotion Detection from Text 
Author: Nastaran Mesgari
Spring 2024


Abstract

Natural language processing faces significant challenges when it comes to text emotion detection because there are few labeled datasets available, and emotions are multi-class issues. This proposal builds an effective model for emotion detection by using labeled data from tweets to address these issues. 

The methodology includes difficult model evaluation metrics, a variety of multiclass classification algorithms, and strong data preprocessing techniques. The creation of a cutting-edge classification model with previously unheard-of accuracy, practical insights into the efficacy of methods, and advancement over current benchmarks are among the anticipated results. The goal of this work is to further the field of text analysis and NLP applications.
Introduction
Emotion detection from text is one of the challenging problems in Natural Language Processing. The reason is the unavailability of labeled datasets and the multi-class nature of the problem. Humans have a variety of emotions, and it is difficult to collect enough records for each emotion and hence the problem of class imbalance arises. Here we have labeled data for emotion detection and the objective is to build an efficient model to detect emotion. 

The data is basically a collection of tweets annotated with the emotions behind them. We have three columns tweet_id, sentiment, and content. In "content" we have the raw tweet. In "sentiment" we have the emotion behind the tweet. Refer to the starter notebook for more insights.
This public domain dataset is collected from ‘dataWorld’ platform. Thanks, ‘dataWorld’ for releasing it under Public License.
The data has 13 different emotions and 40000 records. So, it's challenging to build an efficient multiclass classification model. We may need to logically reduce the number of classes here and use some advanced methods to build an efficient model.


Methodology

1- Data Preprocessing: Implement robust preprocessing techniques, including advanced tokenization, normalization, and noise reduction algorithms.
2- Model Selection: Explore a diverse range of multiclass classification algorithms, including the Decision Tree Model, Random Forest Model, Logistic Regression Model, Multinomial Naive Bayes, and so on to identify the most suitable model for emotion detection.
 3- Model Evaluation: Rigorously evaluate model performance using a comprehensive suite of metrics, including accuracy and area under the ROC curve (AUC).
Expected Outcomes
- Development of a state-of-the-art multiclass classification model that achieves unprecedented accuracy and efficiency in emotion detection from text. (compare different classification algorithms)
 - Generation of actionable insights into the effectiveness of techniques 
- Kaggle results as a benchmark, and improve on them

Conclusion
 This proposal is about the challenging task of emotion detection from text using advanced NLP techniques. By implementing study data preprocessing methods and exploring various multiclass classification algorithms, we expect to develop a modern model with improved accuracy and efficiency.





