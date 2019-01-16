---
layout: post
title: "URNet : User-Resizable Residual Networks with Conditional Gating Module"
date: 2019-01-15 07:26:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Simyung Chang, Sang-ho Lee, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks are widely used to process spatial scenes, but their computational cost is fixed and depends on the structure of the network used. There are methods to reduce the cost by compressing networks or varying its computational path dynamically according to the input image. However, since the user can not control the size of the learned model, it is difficult to respond dynamically if the amount of service requests suddenly increases. We propose User-Resizable Residual Networks (URNet), which allows the user to adjust the scale of the network as needed during evaluation. URNet includes Conditional Gating Module (CGM) that determines the use of each residual block according to the input image and the desired scale. CGM is trained in a supervised manner using the newly proposed scale loss and its corresponding training methods. URNet can control the amount of computation according to user's demand without degrading the accuracy significantly. It can also be used as a general compression method by fixing the scale size during training. In the experiments on ImageNet, URNet based on ResNet-101 maintains the accuracy of the baseline even when resizing it to approximately 80% of the original network, and demonstrates only about 1% accuracy degradation when using about 65% of the computation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04687](https://arxiv.org/abs/1901.04687)

##### PDF
[https://arxiv.org/pdf/1901.04687](https://arxiv.org/pdf/1901.04687)

