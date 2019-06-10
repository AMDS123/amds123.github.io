---
layout: post
title: "AutoGrow: Automatic Layer Growing in Deep Convolutional Networks"
date: 2019-06-07 05:54:41
categories: arXiv_CV
tags: arXiv_CV GAN NAS CNN
author: Wei Wen, Feng Yan, Hai Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose AutoGrow to automate depth discovery in Deep Neural Networks (DNNs): starting from a shallow seed architecture, AutoGrow grows new layers if the growth improves the accuracy; otherwise, the growth stops and the network depth is discovered. The residual and plain blocks are used as growing sub-modules to study DNNs with and without shortcuts. We propose generic growing and stopping policies to minimize human efforts spent on the optimal depth search. Our experiments show that by applying the same policy to different tasks, AutoGrow can always discover network depth effectively and achieve state-of-the-art accuracy on various datasets of MNIST, FashionMNIST, SVHN, CIFAR10, CIFAR100 and ImageNet. Comparing to Neural Architecture Search (NAS) that often designs a gigantic search space and consumes tremendous resources, AutoGrow lies at the other end of the research spectrum: it focuses on efficient depth discovery and reduces the growing and searching time to a level similar to that of training a single DNN. Thus, AutoGrow is able to scale up to large datasets such as ImageNet. Our study also reveals that previous Network Morphism is sub-optimal for increasing layer depth. Finally, we demonstrate that AutoGrow enables the training of deeper plain networks, which has been problematic even using Batch Normalization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02909](http://arxiv.org/abs/1906.02909)

##### PDF
[http://arxiv.org/pdf/1906.02909](http://arxiv.org/pdf/1906.02909)

