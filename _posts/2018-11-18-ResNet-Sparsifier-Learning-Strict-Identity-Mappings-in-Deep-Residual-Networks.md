---
layout: post
title: "ResNet Sparsifier: Learning Strict Identity Mappings in Deep Residual Networks"
date: 2018-11-18 23:43:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Optimization Detection Recognition
author: Xin Yu, Zhiding Yu, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
A family of super deep networks, referred to as residual networks or ResNet, achieved record-beating performance in various visual tasks such as image recognition, object detection, and semantic segmentation. The ability to train very deep networks naturally pushed the researchers to use enormous resources to achieve the best performance. Consequently, in many applications super deep residual networks were employed for just a marginal improvement in performance. In this paper, we propose epsilon-ResNet that allows us to automatically discard redundant layers, which produces responses that are smaller than a threshold epsilon, with a marginal or no loss in performance. The epsilon-ResNet architecture can be achieved using a few additional rectified linear units in the original ResNet. Our method does not use any additional variables nor numerous trials like other hyper-parameter optimization techniques. The layer selection is achieved using a single training process and the evaluation is performed on CIFAR-10, CIFAR-100, SVHN, and ImageNet datasets. In some instances, we achieve about 80% reduction in the number of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.01661](http://arxiv.org/abs/1804.01661)

##### PDF
[http://arxiv.org/pdf/1804.01661](http://arxiv.org/pdf/1804.01661)

