---
layout: post
title: "ADA-Tucker: Compressing Deep Neural Networks via Adaptive Dimension Adjustment Tucker Decomposition"
date: 2019-06-18 16:19:04
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Zhisheng Zhong, Fangyin Wei, Zhouchen Lin, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of deep learning models in numerous applications, their widespread use on mobile devices is seriously impeded by storage and computational requirements. In this paper, we propose a novel network compression method called Adaptive Dimension Adjustment Tucker decomposition (ADA-Tucker). With learnable core tensors and transformation matrices, ADA-Tucker performs Tucker decomposition of arbitrary-order tensors. Furthermore, we propose that weight tensors in networks with proper order and balanced dimension are easier to be compressed. Therefore, the high flexibility in decomposition choice distinguishes ADA-Tucker from all previous low-rank models. To compress more, we further extend the model to Shared Core ADA-Tucker (SCADA-Tucker) by defining a shared core tensor for all layers. Our methods require no overhead of recording indices of non-zero elements. Without loss of accuracy, our methods reduce the storage of LeNet-5 and LeNet-300 by ratios of 691 times and 233 times, respectively, significantly outperforming state of the art. The effectiveness of our methods is also evaluated on other three benchmarks (CIFAR-10, SVHN, ILSVRC12) and modern newly deep networks (ResNet, Wide-ResNet).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07671](http://arxiv.org/abs/1906.07671)

##### PDF
[http://arxiv.org/pdf/1906.07671](http://arxiv.org/pdf/1906.07671)

