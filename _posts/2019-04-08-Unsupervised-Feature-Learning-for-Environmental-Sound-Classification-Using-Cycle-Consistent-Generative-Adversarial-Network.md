---
layout: post
title: "Unsupervised Feature Learning for Environmental Sound Classification Using Cycle Consistent Generative Adversarial Network"
date: 2019-04-08 17:44:14
categories: arXiv_SD
tags: arXiv_SD Adversarial Object_Detection CNN Classification Detection
author: Mohammad Esmaeilpour, Patrick Cardinal, Alessandro L. Koerich
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel environmental sound classification approach incorporating unsupervised feature learning from codebook via spherical $K$-Means++ algorithm and a new architecture for high-level data augmentation. The audio signal is transformed into a 2D representation using a discrete wavelet transform (DWT). The DWT spectrograms are then augmented by a novel architecture for cycle-consistent generative adversarial network. This high-level augmentation bootstraps generated spectrograms in both intra and inter class manners by translating structural features from sample to sample. A codebook is built by coding the DWT spectrograms with the speeded-up robust feature detector (SURF) and the K-Means++ algorithm. The Random Forest is our final learning algorithm which learns the environmental sound classification task from the clustered codewords in the codebook. Experimental results in four benchmarking environmental sound datasets (ESC-10, ESC-50, UrbanSound8k, and DCASE-2017) have shown that the proposed classification approach outperforms the state-of-the-art classifiers in the scope, including advanced and dense convolutional neural networks such as AlexNet and GoogLeNet, improving the classification rate between 3.51% and 14.34%, depending on the dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04221](http://arxiv.org/abs/1904.04221)

##### PDF
[http://arxiv.org/pdf/1904.04221](http://arxiv.org/pdf/1904.04221)

