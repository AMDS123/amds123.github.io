---
layout: post
title: "An Improved Trade-off Between Accuracy and Complexity with Progressive Gradient Pruning"
date: 2019-06-20 16:46:16
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Recognition
author: Le Thanh Nguyen-Meidine, Eric Granger, Madhu Kiran, Louis-Antoine Blais-Morin
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep neural networks (NNs) have achieved state-of-the-art accuracy in many visual recognition tasks ,the growing computational complexity and energy consumption of networks remains an issue, especially for applications on platforms with limited resources and requiring real-time processing. Channel pruning techniques have recently shown promising results for the compression of convolutional NNs (CNNs). However, these techniques can result in low accuracy and complex optimisations because some only prune after training CNNs, while others prune from scratch during training by integrating sparsity constraints or modifying the loss function. The progressive soft filter pruning technique provides greater training efficiency, but its soft pruning strategy does no thandle the backward pass which is needed for better optimization. In this paper, a new Progressive Gradient Pruning (PGP) technique is proposed for iterative channel pruning during training. It relies on a criterion that measures the change in channel weights that improves existing progressive pruning, and on an effective hard and soft pruning strategies to adapt momentum tensors during the backward propagation pass. Experimental results obtained after training various CNNs on the MNIST and CIFAR10 datasets indicate that the PGP technique canachieve a better tradeoff between classification accuracy and network (time and memory) complexity than state-of-the-art channel pruning techniques

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08746](http://arxiv.org/abs/1906.08746)

##### PDF
[http://arxiv.org/pdf/1906.08746](http://arxiv.org/pdf/1906.08746)

