# NaiveBayesTextClassifierWikipedia
This code is implementing a Naive Bayes classifier for text classification. The classifier is trained on two classes: "sports" and "politics." It uses the Wikipedia API to fetch documents for these classes, preprocesses the text data, calculates class probabilities, and conditional probabilities of each token given the class. The trained model is then saved to a file named 'probabilities.pkl.' Finally, a prediction function is defined to classify a test document into one of the two classes based on the trained model.
