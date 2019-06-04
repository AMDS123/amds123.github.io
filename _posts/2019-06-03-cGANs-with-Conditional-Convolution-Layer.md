---
layout: post
title: "cGANs with Conditional Convolution Layer"
date: 2019-06-03 11:15:51
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Min-Cheol Sagong, Yong-Goo Shin, Yoon-Jae Yeo, Seung Park, Sung-Jea Ko
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional generative adversarial networks (cGANs) have been widely researched to generate class conditional images using a single generator. However, in the conventional cGANs techniques, it is still challenging for the generator to learn condition-specific features, since a standard convolutional layer with the same weights is used regardless of the condition. In this paper, we propose a novel convolution layer, called the conditional convolution layer, which directly generates different feature maps by employing the weights which are adjusted depending on the conditions. More specifically, in each conditional convolution layer, the weights are conditioned in a simple but effective way through filter-wise scaling and channel-wise shifting operations. In contrast to the conventional methods, the proposed method with a single generator can effectively handle condition-specific characteristics. The experimental results on CIFAR, LSUN and ImageNet datasets show that the generator with the proposed conditional convolution layer achieves a higher quality of conditional image generation than that with the standard convolution layer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00709](http://arxiv.org/abs/1906.00709)

##### PDF
[http://arxiv.org/pdf/1906.00709](http://arxiv.org/pdf/1906.00709)

