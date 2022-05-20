# MNIST inference
Perform MNIST inference by converting a pre-trained ANN to an SNN
## Presenting a single image
Create a simple three layer network of integrate-and-fire neurons, densely connected with pre-trained weights. Present a single MNIST image and visualise spiking activity.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mnist_inference/tutorial_1.ipynb)

## Classifying entire test set</h3>
Present entire MNIST test set to previous model and calculate accuracy.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mnist_inference/tutorial_2.ipynb)

## Improve classification performance</h3>
Use parallel batching and custom updates to improve inference performance by over 30x compared to previous tutorial.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mnist_inference/tutorial_3.ipynb)
