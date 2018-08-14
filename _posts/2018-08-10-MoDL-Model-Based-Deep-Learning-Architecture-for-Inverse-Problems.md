---
layout: post
title: "MoDL: Model Based Deep Learning Architecture for Inverse Problems"
date: 2018-08-10 18:41:30
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization Deep_Learning
author: Hemant Kumar Aggarwal, Merry P. Mani, Mathews Jacob
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a model-based image reconstruction framework with a convolution neural network (CNN) based regularization prior. The proposed formulation provides a systematic approach for deriving deep architectures for inverse problems with the arbitrary structure. Since the forward model is explicitly accounted for, a smaller network with fewer parameters is sufficient to capture the image information compared to black-box deep learning approaches, thus reducing the demand for training data and training time. Since we rely on end-to-end training, the CNN weights are customized to the forward model, thus offering improved performance over approaches that rely on pre-trained denoisers. The main difference of the framework from existing end-to-end training strategies is the sharing of the network weights across iterations and channels. Our experiments show that the decoupling of the number of iterations from the network complexity offered by this approach provides benefits including lower demand for training data, reduced risk of overfitting, and implementations with significantly reduced memory footprint. We propose to enforce data-consistency by using numerical optimization blocks such as conjugate gradients algorithm within the network; this approach offers faster convergence per iteration, compared to methods that rely on proximal gradients steps to enforce data consistency. Our experiments show that the faster convergence translates to improved performance, especially when the available GPU memory restricts the number of iterations.

##### Abstract (translated by Google)
我们介绍了一种基于模型的图像重建框架，该框架采用基于卷积神经网络（CNN）的正则化先验。所提出的公式提供了一种系统方法，用于推导任意结构的逆问题的深层架构。由于明确考虑了正向模型，与黑盒深度学习方法相比，具有较少参数的较小网络足以捕获图像信息，因此减少了对训练数据和训练时间的需求。由于我们依靠端到端培训，CNN权重是针对正向模型定制的，因此与依赖于预训练的降噪器的方法相比，提供了更好的性能。框架与现有端到端培训策略的主要区别在于跨迭代和通道共享网络权重。我们的实验表明，这种方法提供的迭代次数与网络复杂性的解耦提供了诸多益处，包括对培训数据的需求降低，过度拟合的风险降低以及内存占用大大减少的实现。我们建议通过使用网络内的共轭梯度算法等数值优化块来强制实现数据一致性。与依赖于近端梯度步骤来强制数据一致性的方法相比，这种方法每次迭代提供更快的收敛。我们的实验表明，更快的收敛转化为改进的性能，尤其是当可用的GPU内存限制了迭代次数时。

##### URL
[http://arxiv.org/abs/1712.02862](http://arxiv.org/abs/1712.02862)

##### PDF
[http://arxiv.org/pdf/1712.02862](http://arxiv.org/pdf/1712.02862)

