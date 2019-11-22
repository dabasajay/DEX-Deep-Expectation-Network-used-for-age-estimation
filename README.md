# Computer Vision Class Project: Deep EXpectation (DEX) Network used for age estimation

[![Issues](https://img.shields.io/github/issues/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/issues)
[![Forks](https://img.shields.io/github/forks/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/network)
[![Stars](https://img.shields.io/github/stars/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/stargazers)
[![Ajay Dabas](https://img.shields.io/badge/Ajay-Dabas-825ee4.svg)](https://dabasajay.github.io/)

## Table of Contents

1. [Summary](#Summary)
2. [Requirements](#Requirements)
3. [Training parameters and results](#training-parameters-and-results)
4. [References](#References)


## Summary

The estimation of apparent age in still face images with deep learning uses the VGG-19 architecture. The age regression problem is posed as a deep classification problem followed by a softmax expected value refinement and show improvements over direct regression training of CNNs. Deep EXpectation (DEX) of apparent age, uses an ensemble of 3 (Original paper uses 20) VGG19 networks to predict the age.

## Requirements

Recommended System Requirements to train model.

<ul type="square">
	<li>A good CPU and a GPU with atleast 8GB memory</li>
	<li>Atleast 8GB of RAM</li>
	<li>Active internet connection so that keras can download VGG19 model weights</li>
</ul>

Required libraries for Python along with their version numbers used while making & testing of this project

<ul type="square">
	<li>Python - 3.6.7</li>
	<li>Numpy - 1.16.4</li>
	<li>Tensorflow - 1.13.1</li>
	<li>Keras - 2.2.4</li>
	<li>PIL - 4.3.0</li>
	<li>tqdm - 4.28.1</li>
</ul>

<strong>Dataset:</strong> <a href="https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/wiki_crop.tar">Download link</a>

## Training parameters and results

| Training parameters | Results |
| :--- | :--- |
| <ul><li></li></ul> | <img width="50%" src="https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/raw/master/result.jpg" alt="Result Image"> |

## References

<ul type="square">
	<li><a href="https://link.springer.com/content/pdf/10.1007%2Fs11263-016-0940-3.pdf">“Deep EXpectation of real and apparent age from a single image without facial landmarks”, 2018 International Journal of Computer Vision 126:144-157</a></li>
	<li><a href="https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki">All Datasets Link</a></li>
</ul>
