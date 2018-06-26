# NLP Scientific Text Prediction

Generating syntactically correct sentences through Bayesian approach and LSTM networks.

First (ScientificGibberish.ipynb): Implemented N-gram model with maximum likelihood prediction to generate scientific text, based on corpus of my PhD thesis (corpus not provided, but can be substituted with any long text). Predictions were highly repetitive, so improved them by adding randomized noise on top of maximum likelihood method.

Next (in progress): currently implementing static LSTM network, using TensorFlow. Accuracy is still very low for the medium-length texts of my PhD thesis, higher accuracy was seen for ~100 word length texts. Working on the details...
