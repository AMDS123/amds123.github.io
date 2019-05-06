---
layout: post
title: "Learning Transferable Architectures for Scalable Image Recognition"
date: 2018-04-11 05:12:21
categories: arXiv_CV
tags: arXiv_CV Regularization NAS CNN Image_Classification Classification Recognition
author: Barret Zoph, Vijay Vasudevan, Jonathon Shlens, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Developing neural network image classification models often requires significant architecture engineering. In this paper, we study a method to learn the model architectures directly on the dataset of interest. As this approach is expensive when the dataset is large, we propose to search for an architectural building block on a small dataset and then transfer the block to a larger dataset. The key contribution of this work is the design of a new search space (the "NASNet search space") which enables transferability. In our experiments, we search for the best convolutional layer (or "cell") on the CIFAR-10 dataset and then apply this cell to the ImageNet dataset by stacking together more copies of this cell, each with their own parameters to design a convolutional architecture, named "NASNet architecture". We also introduce a new regularization technique called ScheduledDropPath that significantly improves generalization in the NASNet models. On CIFAR-10 itself, NASNet achieves 2.4% error rate, which is state-of-the-art. On ImageNet, NASNet achieves, among the published works, state-of-the-art accuracy of 82.7% top-1 and 96.2% top-5 on ImageNet. Our model is 1.2% better in top-1 accuracy than the best human-invented architectures while having 9 billion fewer FLOPS - a reduction of 28% in computational demand from the previous state-of-the-art model. When evaluated at different levels of computational cost, accuracies of NASNets exceed those of the state-of-the-art human-designed models. For instance, a small version of NASNet also achieves 74% top-1 accuracy, which is 3.1% better than equivalently-sized, state-of-the-art models for mobile platforms. Finally, the learned features by NASNet used with the Faster-RCNN framework surpass state-of-the-art by 4.0% achieving 43.1% mAP on the COCO dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1707.07012](https://arxiv.org/abs/1707.07012)

##### PDF
[https://arxiv.org/pdf/1707.07012](https://arxiv.org/pdf/1707.07012)

