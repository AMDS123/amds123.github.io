---
layout: post
title: "Self-Binarizing Networks"
date: 2019-02-02 14:48:16
categories: arXiv_CV
tags: arXiv_CV Classification
author: Fayez Lahoud, Radhakrishna Achanta, Pablo M&#xe1;rquez-Neila, Sabine S&#xfc;sstrunk
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to train self-binarizing neural networks, that is, networks that evolve their weights and activations during training to become binary. To obtain similar binary networks, existing methods rely on the sign activation function. This function, however, has no gradients for non-zero values, which makes standard backpropagation impossible. To circumvent the difficulty of training a network relying on the sign activation function, these methods alternate between floating-point and binary representations of the network during training, which is sub-optimal and inefficient. We approach the binarization task by training on a unique representation involving a smooth activation function, which is iteratively sharpened during training until it becomes a binary representation equivalent to the sign activation function. Additionally, we introduce a new technique to perform binary batch normalization that simplifies the conventional batch normalization by transforming it into a simple comparison operation. This is unlike existing methods, which are forced to the retain the conventional floating-point-based batch normalization. Our binary networks, apart from displaying advantages of lower memory and computation as compared to conventional floating-point and binary networks, also show higher classification accuracy than existing state-of-the-art methods on multiple benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00730](http://arxiv.org/abs/1902.00730)

##### PDF
[http://arxiv.org/pdf/1902.00730](http://arxiv.org/pdf/1902.00730)

