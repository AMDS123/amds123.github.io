---
layout: post
title: "Convolutional Neural Networks with Layer Reuse"
date: 2019-01-28 11:45:50
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification RNN Classification
author: Okan K&#xf6;p&#xfc;kl&#xfc;, Maryam Babaee, Gerhard Rigoll
mathjax: true
---

* content
{:toc}

##### Abstract
A convolutional layer in a Convolutional Neural Network (CNN) consists of many filters which apply convolution operation to the input, capture some special patterns and pass the result to the next layer. If the same patterns also occur at the deeper layers of the network, why wouldn't the same convolutional filters be used also in those layers? In this paper, we propose a CNN architecture, Layer Reuse Network (LruNet), where the convolutional layers are used repeatedly without the need of introducing new layers to get a better performance. This approach introduces several advantages: (i) Considerable amount of parameters are saved since we are reusing the layers instead of introducing new layers, (ii) the Memory Access Cost (MAC) can be reduced since reused layer parameters can be fetched only once, (iii) the number of nonlinearities increases with layer reuse, and (iv) reused layers get gradient updates from multiple parts of the network. The proposed approach is evaluated on CIFAR-10, CIFAR-100 and Fashion-MNIST datasets for image classification task, and layer reuse improves the performance by 5.14%, 5.85% and 2.29%, respectively. The source code and pretrained models are publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09615](http://arxiv.org/abs/1901.09615)

##### PDF
[http://arxiv.org/pdf/1901.09615](http://arxiv.org/pdf/1901.09615)

