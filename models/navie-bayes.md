## Key Terms
# Model
An approximation of a relationship between an input and an output.

# Heuristic
An approach to finding a solution which is typically faster but less accurate than some optimal solution.

# Bernoulli Distribution
A distribution which evaluates a particular outcome as binary. In the Bernoulli Naive Bayes classifier case, a word was either in a message or not in a message, which is binary representation.

# Prior
Indicates the probability of a particular class regardless of the features of some example.

# Likelihood
The probability of some features given a particular class.

# Evidence
The denominator of the Naive Bayes classifier.
The probability of a class given some features.
The list of words that the Naive Bayes classifier recognizes.

# Laplace Smoothing
A type of additive smoothing which mitigates the chance of encountering zero probabilities within the Naive Bayes classifier.

# Tokenization
The splitting of some raw textual input into individual words or elements.

# Featurization
The process of transforming raw inputs into something a model can perform training and predictions on.

# Vectorizer
Used in a step of featurizing. It transforms some input into something else. One example is a binary vectorizer which transforms tokenized messages into a binary vector indicating which items in the vocabulary appear in the message.

# Stop Word
A word, typically discarded, which doesn't add much predictive value.

# Stemming
Removing the ending modifiers of words, leaving the stem of the word.

# Lemmatization
A more calculated form of stemming which ensures the proper lemma results from removing the word modifiers.