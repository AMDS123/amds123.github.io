---
layout: post
title: "Sharing Residual Units Through Collective Tensor Factorization in Deep Neural Networks"
date: 2017-03-15 15:00:26
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Classification
author: Chen Yunpeng, Jin Xiaojie, Kang Bingyi, Feng Jiashi, Yan Shuicheng
mathjax: true
---

* content
{:toc}

##### Abstract
Residual units are wildly used for alleviating optimization difficulties when building deep neural networks. However, the performance gain does not well compensate the model size increase, indicating low parameter efficiency in these residual units. In this work, we first revisit the residual function in several variations of residual units and demonstrate that these residual functions can actually be explained with a unified framework based on generalized block term decomposition. Then, based on the new explanation, we propose a new architecture, Collective Residual Unit (CRU), which enhances the parameter efficiency of deep neural networks through collective tensor factorization. CRU enables knowledge sharing across different residual units using shared factors. Experimental results show that our proposed CRU Network demonstrates outstanding parameter efficiency, achieving comparable classification performance to ResNet-200 with the model size of ResNet-50. By building a deeper network using CRU, we can achieve state-of-the-art single model classification accuracy on ImageNet-1k and Places365-Standard benchmark datasets. (Code and trained models are available on GitHub)

##### Abstract (translated by Google)
当构建深度神经网络时，残余单元被广泛用于缓解优化困难。但是，性能增益并不能很好地补偿模型尺寸的增加，表明这些残差单元的参数效率较低。在这项工作中，我们首先在残差单元的几种变化中重新研究残差函数，并证明这些残差函数实际上可以用基于广义块项分解的统一框架来解释。然后，基于新的解释，提出了一种新的体系结构 - 集合残差单元（Collective Residual Unit，CRU），它通过集合张量分解提高了深度神经网络的参数效率。 CRU使用共享因素可以跨不同的剩余单位进行知识共享。实验结果表明，我们提出的CRU网络具有出色的参数效率，与ResNet-50的模型大小相比，可以达到与ResNet-200相当的分类性能。通过使用CRU构建更深的网络，我们可以在ImageNet-1k和Places365-标准基准数据集上实现最先进的单一模型分类准确性。 （代码和受过训练的模型可以在GitHub上找到）

##### URL
[https://arxiv.org/abs/1703.02180](https://arxiv.org/abs/1703.02180)

##### PDF
[https://arxiv.org/pdf/1703.02180](https://arxiv.org/pdf/1703.02180)

