#  Supervised deep learning embeddings for the prediction of cervical cancer diagnosis

Machine learning and dimensionality reduction methods for cervical cancer data screening processing and diagnosis prediction.

## Installation
To run the scripts, you need to have installed:
* Python 2.7 or Python 3.5
* pip or pip3
* pandas
* Theano
* Keras
* TensorFlow

### Installation instructions (Python 2.7)
How to install the Python 2.7 libraries on Linux Ubuntu:

`sudo apt-get -y install python-pip`

`sudo -H pip install scikit-learn`

`sudo -H pip install --upgrade https://github.com/Theano/Theano/archive/master.zip`

`sudo -H pip install --upgrade https://github.com/Lasagne/Lasagne/archive/master.zip`

`sudo -H pip install tensorflow==1.5`

`sudo -H pip install keras`

Set keras to use Theano as a backend instead of TensorFlow:

`sudo vi ~/.keras/keras.json`

(change backend from `tensorflow` to `theano`)

`sudo -H pip install pandas`

### Installation instructions (Python 3.5)
How to install the Python 3.5 libraries on Linux Ubuntu:

`sudo apt-get install python3-pip`

`sudo -H pip3 install scikit-learn`

`sudo -H pip3 install --upgrade https://github.com/Theano/Theano/archive/master.zip`

`sudo -H pip3 install --upgrade https://github.com/Lasagne/Lasagne/archive/master.zip`

`sudo -H pip3 install tensorflow==1.5`

`sudo -H pip3 install keras`

Set keras to use Theano as a backend instead of TensorFlow:

`sudo vi ~/.keras/keras.json`

(change backend from `tensorflow` to `theano`)

## Execution instructions (Python 2.7)
Starting script:

`cd risk-factors-Python2`

`python2 test_deep_architectures.py`

## Execution instructions (Python 3.5)
Starting script:

`cd risk-factors-Python3`

`python3 test_deep_architectures.py`

## Method description and citation
If you use this repository, or you want to know more about the implemented methods, please read and cite this paper:

>  Kelwin Fernandes, Davide Chicco, Jaime S. Cardoso, and Jessica Fernandes, "Supervised deep learning embeddings for the prediction of cervical cancer diagnosis", 2018. *Under revision*.

## Contacts
For scientific questions, or for questions related to the method implementation, please contact Kelwin Fernandes at <[kafc@inesctec.pt](mailto:kafc@inesctec.pt)>

For questions related to this Python 3.5 implementation, please write to Davide Chicco at <[davide.chicco@gmail.com](mailto:davide.chicco@gmail.com)>