# mlGeNN
Perform inference with pre-trained SNNs and train SNNs from scratch with EventProp or e-prop.

## Inference with pre-trained weights
Create a simple three layer network of integrate-and-fire neurons, densely connected with pre-trained weights and evaluate on MNIST test set
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/ml_genn/tutorial_1.ipynb)

## Training from scratch with e-prop
Directly train a simple three layer network of densely connected leaky integrate-and-fire neurons using the e-prop learning rule
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/ml_genn/tutorial_2.ipynb)

## Training from scratch with EventProp
Directly train a simple three layer network of densely connected leaky integrate-and-fire neurons using the EventProp learning rule
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/ml_genn/tutorial_3.ipynb)

## Training using TensorFlow and converting to an SNN using FewSpike
Create and train a simple convolutional neural network in Keras, convert to SNN using [[FewSpike](http://dx.doi.org/10.1038/s42256-021-00311-4)] and evaluate using mlGeNN
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/ml_genn/tutorial_4.ipynb)
