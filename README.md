# NLP-Algorithms
# Probabilistic Language Modeling (N_gram):
Statistical language models, in its essence, are the type of models that assign probabilities to the sequences of words.
You can think of an N-gram as the sequence of N words, by that notion, a 2-gram (or bigram) is a two-word sequence of words like “please turn”, “turn your”, or ”your homework”, and a 3-gram (or trigram) is a three-word sequence of words like “please turn your”, or “turn your homework”
# Smoothing mechanisms in Language Models:
Smoothing mechanisms are used in language models to address the issue of data sparsity and improve the generalization of the model. Data sparsity refers to the problem of encountering unseen or infrequent n-grams in the training data, which can lead to zero probabilities or unreliable probability estimates. 

Smoothing techniques help in the following ways:
1. Avoiding zero probabilities
2. Reducing overfitting
3. Handling data sparsity
4. Improving interpolation and backoff
