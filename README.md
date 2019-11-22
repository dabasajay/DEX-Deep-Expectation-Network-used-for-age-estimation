# Computer Vision Class Project: Deep EXpectation (DEX) Network used for age estimation

[![Issues](https://img.shields.io/github/issues/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/issues)
[![Forks](https://img.shields.io/github/forks/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/network)
[![Stars](https://img.shields.io/github/stars/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation.svg?color=%231155cc)](https://github.com/dabasajay/DEX-Deep-Expectation-Network-used-for-age-estimation/stargazers)
[![Ajay Dabas](https://img.shields.io/badge/Ajay-Dabas-825ee4.svg)](https://dabasajay.github.io/)

## Table of Contents

1. [Summary](#Summary)
2. [Results](#Results)
3. [References](#References)

## Summary

The estimation of apparent age in still face images with deep learning uses the VGG-19 architecture. The age regression problem is posed as a deep classification problem followed by a softmax expected value refinement and show improvements over direct regression training of CNNs. Deep EXpectation (DEX) of apparent age, first detects the face in the test image and then extracts the CNN predictions from an ensemble of 20 networks on the cropped face. The CNNs of DEX were finetuned on the crawled images and then on the provided images with apparent age annotations.

## Results

## References

<ul type="square">
	<li><a href="https://link.springer.com/content/pdf/10.1007%2Fs11263-016-0940-3.pdf">“Deep EXpectation of real and apparent age from a single image without facial landmarks”, 2018 International Journal of Computer Vision 126:144-157</a></li>
	<li><a href="https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/wiki_crop.tar">Dataset Direct Link(Used in this project)</a></li>
	<li><a href="https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki">All Datasets Link</a></li>
</ul>
