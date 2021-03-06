# Project -- Spam Detection using Text Classification based on Natural Language Processing (NLP) Technique 

The objective of the project is to train a spam prediction model for a corpus of text messages. Once there is a new text messages, the spam model is able to predict whether the text message is a spam or not with high accuracy.

The project have four steps. In the first step, the dataset containing 5572 text messages (4825 non-spam messages and 747 spam messages) 
as well as their corresponding label (label "non-spam", also called "ham" and label "spam") were loaded into a data structure called DataFrame. Preprocessing the dataset using NLTK technique made up the second step. It contained removing punctuation, changing all words into lower case, replacing all words into their stemming word, and etc. In the third step of feature extraction, it extracted the most common appeared top 1500 words among all the text messages as the features, making use of bag-of-word technique. In the last step, it trained different types of classification models as well as evaluated their classification accuracy on a test set. Based on the evaluation, the ensemble methods with the highest accuracy of 95.05% was chosen as the best text classifier for spam prediction.

According to the accuracy, the ensemble classifier is very competitive as compared to other spam detector.
