# Sentiment analysis for movie reviews using Deep neural networks

Sentiment classification of movie reviews using RNN, LSTM, GRU and CNN using randomized or GloVe word embeddings. Part of Deep learning for NLP course taken with [Prof. Cornelia Caragea](https://cs.uic.edu/~cornelia/) in Fall 19 semester at the University of Illinois at Chicago.

* as2_dl4nlp.ipynb : Models for RNN, LSTM and GRU with results using Tensorflow.
* as3_dl4nlp.ipynb : Models for CNN with results using keras.

### Requirements:
* Tensorflow v1.0
* Keras
* Numpy
* PyDrive
* [GloVe embeddings](https://nlp.stanford.edu/projects/glove/) 
  > Embeddings used: Wikipedia 2014 + Gigaword 5 (6B tokens, 400K vocab, uncased, 50d, 100d, 200d, & 300d vectors, 822 MB download)
  
### Dataset Used:
* [Sentiment polarity dataset](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
  > Download the files: sentence polarity dataset v1.0. Introduced by Bo Pang and Lillian Lee, Seeing stars: Exploiting class relationships for sentiment categorization with respect to rating scales, Proceedings of ACL 2005.
* [Stanford Sentiment Treebank](https://nlp.stanford.edu/sentiment/)
  > Download the version: Main zip file with readme (6mb). Introduced by Recursive Deep Models for Semantic Compositionality Over a Sentiment TreebankRichard Socher, Alex Perelygin, Jean Wu, Jason Chuang, Christopher Manning, Andrew Ng and Christopher Potts Conference on Empirical Methods in Natural Language Processing (EMNLP 2013)
  
Reviews from the Stanford Sentiment Treebank were used and the labelling was done using the sentiment polarity of those in Sentiment polarity dataset. Sentences present in both were used for our neural nets.

