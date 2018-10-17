---
layout: post
title: "Dynamic Channel Pruning: Feature Boosting and Suppression"
date: 2018-10-12 03:00:59
categories: arXiv_CV
tags: arXiv_CV Salient CNN Classification Gradient_Descent
author: Xitong Gao, Yiren Zhao, Lukasz Dudziak, Robert Mullins, Cheng-zhong Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Making deep convolutional neural networks more accurate typically comes at the cost of increased computational and memory resources. In this paper, we exploit the fact that the importance of features computed by convolutional layers is highly input-dependent, and propose feature boosting and suppression (FBS), a new method to predictively amplify salient convolutional channels and skip unimportant ones at run-time. FBS introduces small auxiliary connections to existing convolutional layers. In contrast to channel pruning methods which permanently remove channels, it preserves the full network structures and accelerates convolution by dynamically skipping unimportant input and output channels. FBS-augmented networks are trained with conventional stochastic gradient descent, making it readily available for many state-of-the-art CNNs. We compare FBS to a range of existing channel pruning and dynamic execution schemes and demonstrate large improvements on ImageNet classification. Experiments show that FBS can accelerate VGG-16 by $5\times$ and improve the speed of ResNet-18 by $2\times$, both with less than $0.6\%$ top-5 accuracy loss.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05331](https://arxiv.org/abs/1810.05331)

##### PDF
[https://arxiv.org/pdf/1810.05331](https://arxiv.org/pdf/1810.05331)

