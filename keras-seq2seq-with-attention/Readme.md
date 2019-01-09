# Implementing Seq2Seq With Attention Using Keras

The Jupyter notebook in this directory demonstrates the implementation of a clean, object-oriented Seq2Seq machine learning model which
is built on top of Keras while using the Tensorflow backend. Later in the notebook, attention is added to the model to improve performance
on longer sequences.

The model implemented in this notebook is useful for getting started in machine translation and natural language processing.

Also included in a separate python file is the implementation of an LSTM with attention. This can be downloaded and used with
your own scripts.

[alt text](https://github.com/neonbjb/ml-notebooks/raw/master/keras-seq2seq-with-attention/attn_plot.png "Attention Plot")

### Prerequisites

You'll need to install [Tensorflow](https://www.tensorflow.org/install/) and [Jupyter](https://jupyter.org/install) at a minimum in order to run the notebook. Training this network has an enormous
computational workload due to the high dimensionality of the input space (words are encoded as one-hot vectors on the input side).
If you want to follow this notebook, I would recommend a newer Nvidia graphics card to perform the computational workload. Otherwise,
you should use Google Colab.

## Acknowledgments

* Tensorflow Seq2Seq sample/tutorial: [here](https://github.com/tensorflow/tensorflow/blob/r1.11/tensorflow/contrib/eager/python/examples/nmt_with_attention/nmt_with_attention.ipynb)
* Official Keras Seq2Seq tutorial: [here](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)
* Attention in Keras: [here](https://medium.com/datalogue/attention-in-keras-1892773a4f22)
