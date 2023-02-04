# CA02
In this exercise, we'll train a model to distinguish between spam and non-spam emails using Naive Bayes. The training set consists of 702 emails, split evenly between spam and non-spam. We'll then test the model on 260 emails and compare its predictions with the actual classifications.

To implement Naive Bayes (Gaussian) follow these steps:

1. Set up a Google Colab file and import necessary files
2. Clean and pre-process the data, removing stop words and infrequent words
3. Create a dictionary of the top 3000 words
4. Generate a frequency and word label matrix
5. Select the Gaussian Naive Bayes Classifier as the model to use
6. Evaluate the accuracy score
