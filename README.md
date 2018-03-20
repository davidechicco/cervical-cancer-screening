#  Supervised deep learning embeddings for the prediction of cervical cancer diagnosis (Python 3.5 version)

Machine learning and dimensionality reduction methods for cervical cancer data screening processing and diagnosis prediction.

## Installation
To run the scripts, you need to have installed:
* Python 2.7 or Python 3.5
* Theano
* Keras
* TensorFlow

How to install the Python 3.5 libraries on Linux Ubuntu:

`sudo -H pip3 install scikit-learn`

`sudo -H pip3 install --upgrade https://github.com/Theano/Theano/archive/master.zip`

`sudo -H pip3 install --upgrade https://github.com/Lasagne/Lasagne/archive/master.zip`

`sudo -H pip3 install tensorflow==1.5`

Set keras to use Theano as a backend instead of TensorFlow:

`sudo vi ~/.keras/keras.json`

(change backend from `tensorflow` to `theano`)

## Instructions

### Python 2.7
Starting script:

`cd risk-factors-Python2`

`python2 test_deep_architectures.py`

### Python 3.5
Starting script:

`cd risk-factors-Python3`

`python3 test_deep_architectures.py`

## Method description and citation
If you use this repository, or you want to know more about the implemented methods, please read and cite this paper:

>  Kelwin Fernandes, Davide Chicco, Jaime S. Cardoso, and Jessica Fernandes, "Supervised deep learning embeddings for the prediction of cervical cancer diagnosis", 2018. *Under revision*.

## Contacts
For scientific questions, or for questions related to the method implementation, please contact Kelwin Fernandes at <[kafc@inesctec.pt](mailto:kafc@inesctec.pt)>

For questions related to this Python 3.5 implementation, please write to Davide Chicco at <[davide.chicco@gmail.com](mailto:davide.chicco@gmail.com)>