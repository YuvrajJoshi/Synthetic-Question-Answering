# Synthetic-Question-Answering
## End to End Networks research paper task: Synthetic Question Answering implementation.

This code implements the [bAbI Facebook Research](https://research.fb.com/downloads/babi/) paper published on [End to End Networks](https://arxiv.org/pdf/1503.08895.pdf)
; particularly the task of *Synthetic Question Answering* using the bAbI dataset.

## About
A given QA task consists of a set of statements, followed by a question whose answer is typically a single word ("yes" or "no").
Our task is to use the answers available to the model at training time to predict the answers at test time.
The model uses Recurrent Neural Networks(RNNs) architecture where the recurrence reads from a possibly large external memory multiple times before outputting a symbol.

## Libraries
  - Numpy
  - Pickle
  - Keras
