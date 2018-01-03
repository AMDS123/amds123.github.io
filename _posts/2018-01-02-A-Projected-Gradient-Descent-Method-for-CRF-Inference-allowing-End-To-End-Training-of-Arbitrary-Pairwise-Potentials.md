---
layout: post
title: "A Projected Gradient Descent Method for CRF Inference allowing End-To-End Training of Arbitrary Pairwise Potentials"
date: 2018-01-02 10:31:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference Deep_Learning Prediction Gradient_Descent
author: M&#xe5;ns Larsson, Anurag Arnab, Fredrik Kahl, Shuai Zheng, Philip Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Are we using the right potential functions in the Conditional Random Field models that are popular in the Vision community? Semantic segmentation and other pixel-level labelling tasks have made significant progress recently due to the deep learning paradigm. However, most state-of-the-art structured prediction methods also include a random field model with a hand-crafted Gaussian potential to model spatial priors, label consistencies and feature-based image conditioning. 
 In this paper, we challenge this view by developing a new inference and learning framework which can learn pairwise CRF potentials restricted only by their dependence on the image pixel values and the size of the support. Both standard spatial and high-dimensional bilateral kernels are considered. Our framework is based on the observation that CRF inference can be achieved via projected gradient descent and consequently, can easily be integrated in deep neural networks to allow for end-to-end training. It is empirically demonstrated that such learned potentials can improve segmentation accuracy and that certain label class interactions are indeed better modelled by a non-Gaussian potential. In addition, we compare our inference method to the commonly used mean-field algorithm. Our framework is evaluated on several public benchmarks for semantic segmentation with improved performance compared to previous state-of-the-art CNN+CRF models.

##### Abstract (translated by Google)
我们是否在视觉社区中流行的条件随机场模型中使用了正确的潜在函数？由于深度学习的范式，语义分割和其他像素级标签任务近来取得了重大进展。然而，大多数最先进的结构化预测方法还包括具有手工制作的高斯势的随机场模型，以对空间先验，标签一致性和基于特征的图像调节进行建模。
 在本文中，我们通过开发一个新的推理和学习框架来挑战这个观点，这个框架可以学习仅仅依赖于图像像素值和支持的大小而受到限制的CRF成对势。考虑标准空间和高维双向内核。我们的框架是基于CRF推断可以通过投影的梯度下降来实现的，因此可以很容易地集成到深度神经网络中，以便进行端到端的训练。经验证明，这种学习的潜力可以提高分割的准确性，某些标签类的相互作用确实更好地模拟非高斯的潜力。此外，我们将我们的推理方法与常用的平均场算法进行比较。我们的框架在几个公共的基准评估语义分割，与先前的CNN + CRF模型相比，性能有所提高。

##### URL
[http://arxiv.org/abs/1701.06805](http://arxiv.org/abs/1701.06805)

##### PDF
[http://arxiv.org/pdf/1701.06805](http://arxiv.org/pdf/1701.06805)

