# OpenDIGITS [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/4QuantOSS/OpenDIGITS/master?urlpath=digits)


[![Build Status](https://travis-ci.org/4QuantOSS/OpenDIGITS.svg?branch=master)](https://travis-ci.org/4QuantOSS/OpenDIGITS)

OpenDIGITS (the **D**eep Learning **G**PU **T**raining **S**ystem) is a webapp for training deep learning models.
The currently supported frameworks are: Torch and Tensorflow on Python 3. Keras and Jupyter Notebook support is coming soon.

The primary difference between this and the NVIDIA version is this is designed to be easier to install with python 3 support (pip install soon!) and no old Caffe left-overs

# Installation

| Installation method | Supported platform[s] | Available versions | Instructions |
| --- | --- | --- | --- |
| Source | Ubuntu 14.04, 16.04 | [GitHub tags](https://github.com/4QuantOSS/OpenDIGITS/releases) | [docs/BuildDigits.md](docs/BuildDigits.md) |
| PIP Wheel | OS X, Windows 64 | Coming Soon! | In Preparation |


# Usage

Once you have installed DIGITS, visit [docs/GettingStarted.md](docs/GettingStarted.md) for an introductory walkthrough.

Then, take a look at some of the other documentation at [docs/](docs/) and [examples/](examples/):

* [Getting started with TensorFlow](docs/GettingStartedTensorflow.md)
* [Getting started with Torch](docs/GettingStartedTorch.md)
* [Fine-tune a pretrained model](examples/fine-tuning/README.md)
* [Creating a dataset using data from S3 endpoint](examples/s3/README.md)
* [Train an autoencoder network](examples/autoencoder/README.md)
* [Train a regression network](examples/regression/README.md)
* [Train a Siamese network](examples/siamese/README.md)
* [Train a text classification network](examples/text-classification/README.md)
* [Train an object detection network](examples/object-detection/README.md)
* [Learn more about weight initialization](examples/weight-init/README.md)
* [Use Python layers in your Caffe networks](examples/python-layer/README.md)
* [Download a model and use it to classify an image outside of DIGITS](examples/classification/README.md)
* [Overview of the REST API](docs/API.md)

# Get help

### Installation issues
* First, check out the instructions above



### Bugs and feature requests
* Please let us know by [filing a new issue](https://github.com/4QuantOSS/OpenDIGITS/issues/new)
* Bonus points if you want to contribute by opening a [pull request](https://help.github.com/articles/using-pull-requests/)!
