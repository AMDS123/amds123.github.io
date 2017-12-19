---
layout: post
title: "Deep Boosting: Joint Feature Selection and Analysis Dictionary Learning in Hierarchy"
date: 2015-08-11 09:45:07
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Image_Classification Optimization Classification Gradient_Descent Recognition
author: Zhanglin Peng, Ya Li, Zhaoquan Cai, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This work investigates how the traditional image classification pipelines can be extended into a deep architecture, inspired by recent successes of deep neural networks. We propose a deep boosting framework based on layer-by-layer joint feature boosting and dictionary learning. In each layer, we construct a dictionary of filters by combining the filters from the lower layer, and iteratively optimize the image representation with a joint discriminative-generative formulation, i.e. minimization of empirical classification error plus regularization of analysis image generation over training images. For optimization, we perform two iterating steps: i) to minimize the classification error, select the most discriminative features using the gentle adaboost algorithm; ii) according to the feature selection, update the filters to minimize the regularization on analysis image representation using the gradient descent method. Once the optimization is converged, we learn the higher layer representation in the same way. Our model delivers several distinct advantages. First, our layer-wise optimization provides the potential to build very deep architectures. Second, the generated image representation is compact and meaningful. In several visual recognition tasks, our framework outperforms existing state-of-the-art approaches.

##### Abstract (translated by Google)
这项工作调查了传统的图像分类管道如何能够延伸到一个深层次的架构，受深度神经网络最近的成功启发。我们提出了一个基于逐层联合特征提升和字典学习的深度提升框架。在每一层中，我们通过组合来自下层的滤波器来构造滤波器的字典，并且利用联合的判别生成公式来迭代地优化图像表示，即经验分类误差的最小化以及训练图像上的分析图像生成的正则化。为了优化，我们执行两个迭代步骤：i）为了最小化分类错误，使用温和的adaboost算法来选择最具有判别力的特征; ii）根据特征选择，使用梯度下降方法更新滤波器以最小化分析图像表示的正则化。一旦优化被收敛，我们以相同的方式学习更高层的表示。我们的模型具有几个明显的优势首先，我们的分层优化提供了构建非常深的体系结构的潜力。其次，生成的图像表示是紧凑和有意义的。在几个视觉识别任务中，我们的框架胜过现有的最先进的方法。

##### URL
[https://arxiv.org/abs/1508.01887](https://arxiv.org/abs/1508.01887)

##### PDF
[https://arxiv.org/pdf/1508.01887](https://arxiv.org/pdf/1508.01887)

