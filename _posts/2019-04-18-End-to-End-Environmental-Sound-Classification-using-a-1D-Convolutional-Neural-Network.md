---
layout: post
title: "End-to-End Environmental Sound Classification using a 1D Convolutional Neural Network"
date: 2019-04-18 20:07:03
categories: arXiv_SD
tags: arXiv_SD CNN Classification
author: Sajjad Abdoli, Patrick Cardinal, Alessandro Lameiras Koerich
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an end-to-end approach for environmental sound classification based on a 1D Convolution Neural Network (CNN) that learns a representation directly from the audio signal. Several convolutional layers are used to capture the signal's fine time structure and learn diverse filters that are relevant to the classification task. The proposed approach can deal with audio signals of any length as it splits the signal into overlapped frames using a sliding window. Different architectures considering several input sizes are evaluated, including the initialization of the first convolutional layer with a Gammatone filterbank that models the human auditory filter response in the cochlea. The performance of the proposed end-to-end approach in classifying environmental sounds was assessed on the UrbanSound8k dataset and the experimental results have shown that it achieves 89% of mean accuracy. Therefore, the propose approach outperforms most of the state-of-the-art approaches that use handcrafted features or 2D representations as input. Furthermore, the proposed approach has a small number of parameters compared to other architectures found in the literature, which reduces the amount of data required for training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08990](http://arxiv.org/abs/1904.08990)

##### PDF
[http://arxiv.org/pdf/1904.08990](http://arxiv.org/pdf/1904.08990)

