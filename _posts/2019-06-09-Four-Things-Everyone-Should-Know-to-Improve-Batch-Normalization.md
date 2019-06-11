---
layout: post
title: "Four Things Everyone Should Know to Improve Batch Normalization"
date: 2019-06-09 01:14:48
categories: arXiv_CV
tags: arXiv_CV Regularization Inference
author: Cecilia Summers, Michael J. Dinneen
mathjax: true
---

* content
{:toc}

##### Abstract
A key component of most neural network architectures is the use of normalization layers, such as Batch Normalization. Despite its common use and large utility in optimizing deep architectures that are otherwise intractable, it has been challenging both to generically improve upon Batch Normalization and to understand specific circumstances that lend themselves to other enhancements. In this paper, we identify four improvements to the generic form of Batch Normalization and the circumstances under which they work, yielding performance gains across all batch sizes while requiring no additional computation during training. These contributions include proposing a method for reasoning about the current example in inference normalization statistics which fixes a training vs. inference discrepancy; recognizing and validating the powerful regularization effect of Ghost Batch Normalization for small and medium batch sizes; examining the effect of weight decay regularization on the scaling and shifting parameters; and identifying a new normalization algorithm for very small batch sizes by combining the strengths of Batch and Group Normalization. We validate our results empirically on four datasets: CIFAR-100, SVHN, Caltech-256, and ImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03548](http://arxiv.org/abs/1906.03548)

##### PDF
[http://arxiv.org/pdf/1906.03548](http://arxiv.org/pdf/1906.03548)

