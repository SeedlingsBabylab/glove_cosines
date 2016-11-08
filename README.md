# glove_cosines

This is a python notebook with cosine similarity calculations of word pairs using GloVe.

The model is trained on children's environmental inputs, obtained from [here](https://github.com/benjamincmorris/Semantic-Networks/tree/master/corpora). This data comes from the CHILDES project.

The ipython notebook code requires installing the [original GloVe](https://github.com/stanfordnlp/GloVe) implementation code if you want to train the model yourself. The distance.py in this repo is a modified version of distance.py from the original python wrapper in the GloVe repo. It computes cosine similarity of two provided words instead of showing top N from the whole vector set, given a single word.

If you don't want to train yourself, you don't have to install GloVe, but you'll need numpy. The pretrained vectors are in this repo.
