---
layout: post
title: "Kernel-Induced Label Propagation by Mapping for Semi-Supervised Classification"
date: 2019-05-29 06:23:49
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Recognition
author: Zhao Zhang, Lei Jia, Mingbo Zhao, Guangcan Liu, Meng Wang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Kernel methods have been successfully applied to the areas of pattern recognition and data mining. In this paper, we mainly discuss the issue of propagating labels in kernel space. A Kernel-Induced Label Propagation (Kernel-LP) framework by mapping is proposed for high-dimensional data classification using the most informative patterns of data in kernel space. The essence of Kernel-LP is to perform joint label propagation and adaptive weight learning in a transformed kernel space. That is, our Kernel-LP changes the task of label propagation from the commonly-used Euclidean space in most existing work to kernel space. The motivation of our Kernel-LP to propagate labels and learn the adaptive weights jointly by the assumption of an inner product space of inputs, i.e., the original linearly inseparable inputs may be mapped to be separable in kernel space. Kernel-LP is based on existing positive and negative LP model, i.e., the effects of negative label information are integrated to improve the label prediction power. Also, Kernel-LP performs adaptive weight construction over the same kernel space, so it can avoid the tricky process of choosing the optimal neighborhood size suffered in traditional criteria. Two novel and efficient out-of-sample approaches for our Kernel-LP to involve new test data are also presented, i.e., (1) direct kernel mapping and (2) kernel mapping-induced label reconstruction, both of which purely depend on the kernel matrix between training set and testing set. Owing to the kernel trick, our algorithms will be applicable to handle the high-dimensional real data. Extensive results on real datasets demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12236](http://arxiv.org/abs/1905.12236)

##### PDF
[http://arxiv.org/pdf/1905.12236](http://arxiv.org/pdf/1905.12236)

