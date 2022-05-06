### Simple Dialogue Model using the Cornell Movie Dialogs Corpus [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uTqsG5GLh9HLWoEFOua-ENYlCmqN-kjm)

This project uses the Cornell Movie Dialogs Corpus to train a simple dialogue model using a sequence to sequence (seq2seq) architecture with Bahdanau attention. 

The architecture utilizes a bidirectional GRU as its encoder and two unidirectional GRUs as the decoder. The hidden state information from the encoder is exposed to the decoder via the Bahdanau attention mechanism.
