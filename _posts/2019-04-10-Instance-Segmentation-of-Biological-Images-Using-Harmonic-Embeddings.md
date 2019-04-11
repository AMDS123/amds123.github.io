---
layout: post
title: "Instance Segmentation of Biological Images Using Harmonic Embeddings"
date: 2019-04-10 15:56:16
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Embedding CNN
author: Victor Kulikov, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new instance segmentation approach tailored to biological images, where instances may correspond to individual cells, organisms or plant parts. Unlike instance segmentation for user photographs or road scenes, in biological data object instances may be particularly densely packed, the appearance variation may be particularly low, the processing power may be restricted, while, on the other hand, the variability of sizes of individual instances may be limited. These peculiarities are successfully addressed and exploited by the proposed approach. 
 Our approach describes each object instance using an expectation of a limited number of sine waves with frequencies and phases adjusted to particular object sizes and densities. At train time, a fully-convolutional network is learned to predict the object embeddings at each pixel using a simple pixelwise regression loss, while at test time the instances are recovered using clustering in the embeddings space. In the experiments, we show that our approach outperforms previous embedding-based instance segmentation approaches on a number of biological datasets, achieving state-of-the-art on a popular CVPPP benchmark. Notably, this excellent performance is combined with computational efficiency that is needed for deployment to domain specialists. 
 The source code is publicly available at Github: https://github.com/kulikovv/harmonic

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05257](http://arxiv.org/abs/1904.05257)

##### PDF
[http://arxiv.org/pdf/1904.05257](http://arxiv.org/pdf/1904.05257)

