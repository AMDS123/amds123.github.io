---
layout: post
title: "Towards Learning of Filter-Level Heterogeneous Compression of Convolutional Neural Networks"
date: 2019-04-22 13:43:34
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning
author: Yochai Zur, Chaim Baskin, Evgenii Zheltonozhskii, Brian Chmiel, Itay Evron, Alex M. Bronstein
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning has become a de facto standard in machine learning with convolutional neural networks (CNNs) demonstrating spectacular success on a wide variety of tasks. However, CNNs are typically very demanding computationally at inference time. One of the ways to alleviate this burden on certain hardware platforms is quantization relying on the use of low-precision arithmetic representation for the weights and the activations. Another popular method is the pruning of the number of filters in each layer. While mainstream deep learning methods train the neural networks weights while keeping the network architecture fixed, the emerging neural architecture search (NAS) techniques make the latter also amenable to training. In this paper, we formulate optimal arithmetic bit length allocation and neural network pruning as a NAS problem, searching for the configurations satisfying a computational complexity budget while maximizing the accuracy. We use a differentiable search method based on the continuous relaxation of the search space proposed by Liu et al. (<a href="https://export.arxiv.org/abs/1806.09055">arXiv:1806.09055</a>). We show, by grid search, that heterogeneous quantized networks suffer from a high variance which renders the benefit of the search questionable. For pruning, improvement over homogeneous cases is possible, but it is still challenging to find those configurations with the proposed method. The code is publicly available at https://github.com/yochaiz/Slimmable and https://github.com/yochaiz/darts-UNIQ .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09872](http://arxiv.org/abs/1904.09872)

##### PDF
[http://arxiv.org/pdf/1904.09872](http://arxiv.org/pdf/1904.09872)

