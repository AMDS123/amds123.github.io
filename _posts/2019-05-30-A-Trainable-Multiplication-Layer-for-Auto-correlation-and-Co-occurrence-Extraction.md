---
layout: post
title: "A Trainable Multiplication Layer for Auto-correlation and Co-occurrence Extraction"
date: 2019-05-30 06:21:54
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Hideaki Hayashi, Seiichi Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a trainable multiplication layer (TML) for a neural network that can be used to calculate the multiplication between the input features. Taking an image as an input, the TML raises each pixel value to the power of a weight and then multiplies them, thereby extracting the higher-order local auto-correlation from the input image. The TML can also be used to extract co-occurrence from the feature map of a convolutional network. The training of the TML is formulated based on backpropagation with constraints to the weights, enabling us to learn discriminative multiplication patterns in an end-to-end manner. In the experiments, the characteristics of the TML are investigated by visualizing learned kernels and the corresponding output features. The applicability of the TML for classification and neural network interpretation is also evaluated using public datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12871](http://arxiv.org/abs/1905.12871)

##### PDF
[http://arxiv.org/pdf/1905.12871](http://arxiv.org/pdf/1905.12871)

