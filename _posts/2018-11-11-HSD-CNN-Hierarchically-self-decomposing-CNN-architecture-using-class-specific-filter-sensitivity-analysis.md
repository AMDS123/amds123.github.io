---
layout: post
title: "HSD-CNN: Hierarchically self decomposing CNN architecture using class specific filter sensitivity analysis"
date: 2018-11-11 12:20:18
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: K. SaiRam, Jayanta Mukherjee, Partha Pratim Das, Amit Patra, Tom Michiels, Bert Moons
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional Convolutional neural networks (CNN) are trained on large domain datasets, and are hence typically over-represented and inefficient in limited class applications. An efficient way to convert such large many-class pre-trained networks into small few-class networks is through a hierarchical decomposition of its feature maps. To alleviate this issue, we propose an automated framework for such decomposition in Hierarchically Self Decomposing CNNs (HSD-CNN), in four steps. HSD-CNNs are derived automatically using a class specific filter sensitivity analysis that quantifies the impact of specific features on a class prediction. The decomposed and hierarchical network can be utilized and deployed directly to obtain sub-networks for subset of classes, and it is shown to perform better without the requirement of retraining these sub-networks. Experimental results show that HSD-CNNs generally do not degrade accuracy if the full set of classes are used. However, when operating on known subsets of classes, HSD-CNNs lead to an increased accuracy using a much smaller model size, requiring much less operations. HSD-CNN flow is verified on the CIFAR10, CIFAR100 and CALTECH101 data sets. We report accuracies up to $85.6\%$ ( $94.75\%$ ) on scenarios with 13 ( 4 ) classes of CIFAR100, using a VGG-16 network pretrained on the full data set. In this case, the used HSD-CNN requires $3.97 \times$ fewer parameters and $3.56 \times$ fewer operations than the VGG-16 baseline containing features for all 100 classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04406](http://arxiv.org/abs/1811.04406)

##### PDF
[http://arxiv.org/pdf/1811.04406](http://arxiv.org/pdf/1811.04406)

