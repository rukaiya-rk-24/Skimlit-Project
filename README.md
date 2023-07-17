# Skimlit-Project

In this project I have tried to implement the following research paper from scratch:
https://arxiv.org/pdf/1710.06071.pdf
The dataset I have used is the same as used in the paper.
We are simply just trying to model our paragraph and classify it into various sections of a paragraph.

I have tried to follow 6 approaches to come with a model.
The final accuracy I have achieved is 97% and with an f1 score of 0.97.

The first model is based on the multinomial Naive Bayes theorem, the second model uses a simple Convolution neural network.
The third model uses custom level token embeddings and the fourth one uses the universal-sentence-encoder by tensorflow hub.
The fifth model uses token-based embedding and character-level embedding combined by a concatenation layer.
The sixth model uses token-based embedding, character-level embedding as well as positional-level embedding and total-lines embedding
combined together.
