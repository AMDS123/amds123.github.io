---
layout: post
title: "RNN-based Online Handwritten Character Recognition Using Accelerometer and Gyroscope Data"
date: 2019-07-24 20:44:00
categories: arXiv_CV
tags: arXiv_CV RNN Recognition
author: Davit Soselia, Shota Amashukeli, Irakli Koberidze, Levan Shugliashvili
mathjax: true
---

* content
{:toc}

##### Abstract
This abstract explores an RNN-based approach to online handwritten recognition problem. Our method uses data from an accelerometer and a gyroscope mounted on a handheld pen-like device to train and run a character pre-diction model. We have built a dataset of timestamped gyroscope and accelerometer data gathered during the manual process of handwriting Latin characters, labeled with the character being written; in total, the dataset con-sists of 1500 gyroscope and accelerometer data sequenc-es for 8 characters of the Latin alphabet from 6 different people, and 20 characters, each 1500 samples from Georgian alphabet from 5 different people. with each sequence containing the gyroscope and accelerometer data captured during the writing of a particular character sampled once every 10ms. We train an RNN-based neural network architecture on this dataset to predict the character being written. The model is optimized with categorical cross-entropy loss and RMSprop optimizer and achieves high accuracy on test data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12935](http://arxiv.org/abs/1907.12935)

##### PDF
[http://arxiv.org/pdf/1907.12935](http://arxiv.org/pdf/1907.12935)

