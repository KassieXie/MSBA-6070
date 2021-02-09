# MSBA-6070
 Including class assignments and other course related work
 
# CA2 - Spam E-mail Detection using Naive Bayes Classification Algorithm 

Goal: train the model with set of emails labelled as either from spam or not spam. We shall ask model to predict the category of this emails and compare the accuracy with correct classification that we already know. 

Training size: 702 emails
Testing size: 260 emails

## Assignment Requirements

1. Use the sample code to understand how the problem is solved. 
2. Construct own Colab Notebook using own variables 
3. Showing step by step results with intermittent “print” statements 
4. Explain clearly understanding of the process at every step.

## Language 

The programming language: Python 3

The file format: ipynb 
- Any application that can open .ipynb file will be great, but I highly recommend using Google Colab or Ananconda Jupyter Notebook.

The comment and text language: English 

## Packages Installed 
Python packages: 
os, numpy, Counter from collections, GaussianNB from sklearn.naive_bayes, accuracy_score from sklearn.metrics

- The codes include installing packages are already embeded in this notebook. It shouldn't have problem if you run my code step by step. 

## Expected Outcome
The expected outcome should already be displayed in the notebook under the codes, but feel free to test the code on your own.

## Logic Behind
Naive Bayes methods are a set of supervised learning algorithms based on applying Bayes’ theorem with the “naive” assumption of conditional independence between every pair of features given the value of the class variable. In spite of their apparently over-simplified assumptions, naive Bayes classifiers have worked quite well in many real-world situations, famously document classification and spam filtering. They require a small amount of training data to estimate the necessary parameters. Naive Bayes learners and classifiers can be extremely fast compared to more sophisticated methods. The decoupling of the class conditional feature distributions means that each distribution can be independently estimated as a one dimensional distribution. This in turn helps to alleviate problems stemming from the curse of dimensionality.

Stop words: A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) that a search engine has been programmed to ignore, both when indexing entries for searching and when retrieving them as the result of a search query. We would not want these words to take up space in our database, or taking up valuable processing time. 

Gaussian: GaussianNB implements the Gaussian Naive Bayes algorithm for classification. It is used in classification and it assumes that features follow a normal distribution. (What we use in this assignment)

Multinomial: MultinomialNB implements the naive Bayes algorithm for multinomially distributed data, and is one of the two classic naive Bayes variants used in text classification. It is used for discrete counts. For example, let’s say, we have a text classification problem. Here we can consider bernoulli trials which is one step further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

Bernoulli: BernoulliNB implements the naive Bayes training and classification algorithms for data that is distributed according to multivariate Bernoulli distributions; i.e., there may be multiple features but each one is assumed to be a binary-valued (Bernoulli, boolean) variable. One application would be text classification with ‘bag of words’model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.

The other reasoning behind each part of codes should be explained in the comment inserted in the work, nonetheless, please feel free to ask me any questions or concerns regarding the codes.

## Contributing
Apologize in advance that any pull requests other by the host might be rejected because this is an education repository for personal use. 

Still, welcome to open an issue if you have something want to discuss, or directly contact with me via my email (xxie3@lion.lmu.edu).
