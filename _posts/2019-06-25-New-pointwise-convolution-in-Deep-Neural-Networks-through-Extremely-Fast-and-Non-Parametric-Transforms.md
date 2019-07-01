---
layout: post
title: "New pointwise convolution in Deep Neural Networks through Extremely Fast and Non Parametric Transforms"
date: 2019-06-25 10:47:08
categories: arXiv_CV
tags: arXiv_CV Relation
author: Joonhyun Jeong, Sung-Ho Bae
mathjax: true
---

* content
{:toc}

##### Abstract
Some conventional transforms such as Discrete Walsh-Hadamard Transform (DWHT) and Discrete Cosine Transform (DCT) have been widely used as feature extractors in image processing but rarely applied in neural networks. However, we found that these conventional transforms have the ability to capture the cross-channel correlations without any learnable parameters in DNNs. This paper firstly proposes to apply conventional transforms to pointwise convolution, showing that such transforms significantly reduce the computational complexity of neural networks without accuracy performance degradation. Especially for DWHT, it requires no floating point multiplications but only additions and subtractions, which can considerably reduce computation overheads. In addition, its fast algorithm further reduces complexity of floating point addition from $\mathcal{O}(n^2)$ to $\mathcal{O}(n\log n)$. These nice properties construct extremely efficient networks in the number parameters and operations, enjoying accuracy gain. Our proposed DWHT-based model gained 1.49\% accuracy increase with 79.1\% reduced parameters and 48.4\% reduced FLOPs compared with its baseline model (MoblieNet-V1) on the CIFAR 100 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.12172](http://arxiv.org/abs/1906.12172)

##### PDF
[http://arxiv.org/pdf/1906.12172](http://arxiv.org/pdf/1906.12172)

