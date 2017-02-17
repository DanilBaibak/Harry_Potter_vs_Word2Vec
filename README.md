# Word vectors of Harry Potter

## Overview
The idea is use [Word2Vec](https://code.google.com/archive/p/word2vec/) for find relations between words, map words into 
2D dimensionality, analyze them for the collection of books about [Harry Potter](https://en.wikipedia.org/wiki/Harry_Potter).

## Installation
For installation please use [conda](http://conda.pydata.org/docs/using/index.html). Just run:
```sh
make init
```
After the installation was done successfully, activate your enviroment:
```sh
source activate hp2vec
```
> For using **conda** and **environments**, please read full documentation of [conda](http://conda.pydata.org/docs/using/index.html).

##Usage
After activate source, run `jupyter notebook hp2vec.ipynb`. I saved pre-train model, so load it `w2v.Word2Vec.load('models/500features_35minwords_10context')` and have fun.

The `hp2vec.ipynb` has the precompiled code, so you can see some interesting relations and how the plots look like.
