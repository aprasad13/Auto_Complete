# Language Models: Auto-Complete

In this project, we will build an auto-complete system.  Auto-complete system is something we may see every day
- When we google something, we often have suggestions to help us complete our search. 
- When we are writing an email, we get suggestions telling us possible endings to our sentence.  

## Outline
Here are the steps of this project:

1. Load and preprocess data
    - Load and tokenize data.
    - Split the sentences into train and test sets.
    - Replace words with a low frequency by an unknown marker `<unk>`.
2. Develop <Strong>N-gram</strong> based language models
    - Compute the count of n-grams from a given data set.
    - Estimate the conditional probability of a next word with k-smoothing.
3. Evaluate the N-gram models by computing the <strong>Perplexity Score</strong>.
4. Use the model to suggest an upcoming word given sentence. 
