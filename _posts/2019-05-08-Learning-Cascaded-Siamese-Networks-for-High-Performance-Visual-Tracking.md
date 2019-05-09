---
layout: post
title: "Learning Cascaded Siamese Networks for High Performance Visual Tracking"
date: 2019-05-08 01:06:23
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Classification Deep_Learning Gradient_Descent
author: Peng Gao, Yipeng Ma, Ruyue Yuan, Liyi Xiao, Fei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Visual tracking is one of the most challenging computer vision problems. In order to achieve high performance visual tracking in various negative scenarios, a novel cascaded Siamese network is proposed and developed based on two different deep learning networks: a matching subnetwork and a classification subnetwork. The matching subnetwork is a fully convolutional Siamese network. According to the similarity score between the exemplar image and the candidate image, it aims to search possible object positions and crop scaled candidate patches. The classification subnetwork is designed to further evaluate the cropped candidate patches and determine the optimal tracking results based on the classification score. The matching subnetwork is trained offline and fixed online, while the classification subnetwork performs stochastic gradient descent online to learn more target-specific information. To improve the tracking performance further, an effective classification subnetwork update method based on both similarity and classification scores is utilized for updating the classification subnetwork. Extensive experimental results demonstrate that our proposed approach achieves state-of-the-art performance in recent benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02857](http://arxiv.org/abs/1905.02857)

##### PDF
[http://arxiv.org/pdf/1905.02857](http://arxiv.org/pdf/1905.02857)

