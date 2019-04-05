---
layout: post
title: "Accelerating Deep Unsupervised Domain Adaptation with Transfer Channel Pruning"
date: 2019-03-25 07:32:30
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention CNN Transfer_Learning Classification
author: Chaohui Yu, Jindong Wang, Yiqiang Chen, Zijing Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep unsupervised domain adaptation (UDA) has recently received increasing attention from researchers. However, existing methods are computationally intensive due to the computation cost of Convolutional Neural Networks (CNN) adopted by most work. To date, there is no effective network compression method for accelerating these models. In this paper, we propose a unified Transfer Channel Pruning (TCP) approach for accelerating UDA models. TCP is capable of compressing the deep UDA model by pruning less important channels while simultaneously learning transferable features by reducing the cross-domain distribution divergence. Therefore, it reduces the impact of negative transfer and maintains competitive performance on the target task. To the best of our knowledge, TCP is the first approach that aims at accelerating deep UDA models. TCP is validated on two benchmark datasets-Office-31 and ImageCLEF-DA with two common backbone networks-VGG16 and ResNet50. Experimental results demonstrate that TCP achieves comparable or better classification accuracy than other comparison methods while significantly reducing the computational cost. To be more specific, in VGG16, we get even higher accuracy after pruning 26% floating point operations (FLOPs); in ResNet50, we also get higher accuracy on half of the tasks after pruning 12% FLOPs. We hope that TCP will open a new door for future research on accelerating transfer learning models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.02654](http://arxiv.org/abs/1904.02654)

##### PDF
[http://arxiv.org/pdf/1904.02654](http://arxiv.org/pdf/1904.02654)

