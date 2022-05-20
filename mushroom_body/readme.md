# Insect-inspired MNIST classification
Train a model of the insect mushroom body using an STDP learning rule to classify MNIST.
## Projection Neurons
Create the first layer of <i>Projection Neurons</i> which convert input images into a sparse temporal code.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mushroom_body/1_first_layer.ipynb)

## Kenyon Cells
Add a second, randomly-connected layer of <i>Kenyon Cells</i> to the model.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mushroom_body/2_second_layer.ipynb)

## Kenyon Cell gain control
Add recurrent inhibition circuit, inspired by <i>Giant GABAergic Neuron</i> in locusts, to improve sparse coding of the Kenyon Cells.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mushroom_body/3_second_layer_gain_control.ipynb)

## Mushroom Body Output Neurons</h3>
Add <i>Mushroom Body Output Neurons</i> with STDP learning and train model on MNIST training set.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mushroom_body/4_third_layer.ipynb)

## Testing
Create a simplified copy of the model without learning, load in the trained weights and calculate inference accuracy on MNIST test set.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/genn-team/tutorials/blob/master/mushroom_body/5_testing.ipynb)

