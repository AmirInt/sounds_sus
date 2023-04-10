# sounds_sus

This project implements a linear classifier for sentimental analysis purposes on product reviews. 

## Implementation

### Algorithms

The linear classifier takes advantage of:
- [The perceptron algorithm](https://towardsdatascience.com/perceptron-algorithms-for-linear-classification-e1bb3dcc7602#eecf)
- [The average perceptron algorithm](https://towardsdatascience.com/perceptron-algorithms-for-linear-classification-e1bb3dcc7602#4771)
- [The Pegasos algorithm](https://towardsdatascience.com/perceptron-algorithms-for-linear-classification-e1bb3dcc7602#c466)

### Data Extraction

Use the `use_bigram` in `main.py` to set the language model as bigram (`True`) or unigram (`False`).
Set the `remove_stopwords` variable to choose to remove the predefined stopwords (e.g. i, me, my, myself, etc.) from the extracted dictionary and the generated feature matrices.

## Tests

Run the `test.py` python script for basic validation tests.

## Run

Run the `main.py` python script to see the results.