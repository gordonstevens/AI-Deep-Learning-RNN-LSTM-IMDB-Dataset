### Notebook and dataset backgrounder
I use non-client/customer specific applications of my projects due to privacy, but I would still like to showcase what I have built, so I use public datasets. This project is cross-published on Github and Kaggle.

The Internet Movie Database also known as IMDB is the best place on the Internet to find information about Hollywood productions, TV shows and movies.

A dataset with [25000 movie reviews from IMDB](https://keras.io/api/datasets/imdb/) was compiled by the [Keras team](https://keras.io/). It is great for demonstrating how [Long Short-Term Memory (LSTM)](https://en.wikipedia.org/wiki/Long_short-term_memory), a type of [Recurrent Neural Network (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network) can be used.

### Theory backgrounder
This uses a neural network, a network of processing nodes (perceptrons/neurons) which activate or not dependent upon the mathematical activation equation. These mathematical neurons mimic how we think as humans with our biological neurons. The defacto type of RNN, LSTM is used in this project. As noted by a very good [WikiPedia article](https://en.wikipedia.org/wiki/Recurrent_neural_network), early RNNs had a vanishing gradient problem, so there is nothing to train against.

> Unlike feedforward neural networks, which process data in a single pass, RNNs process data across multiple time steps, making them well-adapted for modelling and processing text, speech, and time series.

### Tech backgrounder
During 2022 and 2023, when I originally learned how to work with Tensorflow and Keras, I learned about various ways to use Keras, and this project is to highlight my use of an RNN, LSTM type. Now in 2024, Keras can be run on top of JAX, Tensorflow, or PyTorch.

Here I will use Tensorflow and Keras, to supplt the dataset and use the LSTM.

### Misc
While the dataset as provided has 25000 reviews in total, I will use 20000 samples, limit each review to a maximum of 150 words, training the model with 15000 samples, and validating the model with 5000 samples. After the model is run, I will be able to determine the number of trainiable parameters are in the model with this build.
