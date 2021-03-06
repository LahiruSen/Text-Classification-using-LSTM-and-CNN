# Text-Classification-using-LSTM-and-CNN
# Introduction
Sequence classification is a predictive modeling problem where you have some sequence of inputs over space or time and the task is to predict a category for the sequence.
What makes this problem difficult is that the sequences can vary in length, be comprised of a very large vocabulary of input symbols and may require the model to learn the long-term context or dependencies between symbols in the input sequence.
Text sentiment analysis is one of the most important tasks in the field
of public opinion monitoring, service evaluation and satisfaction analysis in the current network environment. At present, the sentiment analysis algorithms with good effects are all based on statistical learning methods. The performance of this method depends on the quality of feature extraction, while good feature engineering requires a high degree of expertise and is also time-consuming, laborious, and affords poor opportunities for mobility. Neural networks can reduce dependence on feature engineering.
Recurrent neural networks can obtain context information but the order
of words will lead to bias; the text analysis method based on Convolutional neural network (CNN) can obtain important features of text through pooling but it is difficult to obtain contextual information. 
The basic task of sentiment analysis is to classify the polarity of a given text at the document, sentence or feature/aspect level and to determine whether the opinions expressed in the document, sentence or entity feature/aspect are positive, negative or neutral.
# Problem Description
The problem that we will use to demonstrate text classification in this blog is the IMDB movie review sentiment classification problem. Each movie review is a variable sequence of words and the sentiment of each movie review must be classified.
The IMDB Movie Review Dataset contains 25,000 highly-polar movie reviews (good or bad) for training and the same amount again for testing. The problem is to determine whether a given movie review has a positive or negative sentiment.
Keras provides access to the IMDB dataset built-in. The imdb.load_data() function allows you to load the dataset in a format that is ready for use in neural network and deep learning models.
The words have been replaced by integers that indicate the ordered frequency of each word in the dataset. The sentences in each review are therefore comprised of a sequence of integers.
