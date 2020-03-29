# Predict-Cluster

## Introduction
This repository contains the code for the paper "PREDICT & CLUSTER: Unsupervised Skeleton Based Action Recognition", which is available [here](https://arxiv.org/abs/1911.12409). 
The unsupervised approach implements two strategies discussed in the paper, Fixed-state(FS) and Fixed-weight(FW). It is tested on NW-UCLA and NTU-RGBD(60) dataset.

## Abstract
We propose a novel system for unsupervised skeleton-based action recognition. Given inputs of body-keypoints sequences obtained during various movements, 
our system associates the sequences with actions. Our system is based on an encoder-decoder recurrent neural network, where the encoder learns a separable feature 
representation within its hidden states formed by training the model to perform the prediction task. We show that according to such unsupervised training, the decoder 
and the encoder self-organize their hidden states into a feature space which clusters similar movements into the same cluster and distinct movements into distant clusters.

## Examples
(TBD)

## Requirements
1. Tensorflow 1.14.0
2. Python 3
3. scikit-learn 0.21.2
4. matplotlib 3.1.0
5. numpy 1.16.4
