---
layout: post
title: "Deep Graph Laplacian Regularization"
date: 2018-07-31 02:44:34
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse CNN Deep_Learning
author: Jin Zeng, Jiahao Pang, Wenxiu Sun, Gene Cheung, Ruichao Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to combine the robustness merit of model-based approaches and the learning power of data-driven approaches for image restoration. Specifically, by integrating graph Laplacian regularization as a trainable module into a deep learning framework, we are less susceptible to overfitting than pure CNN-based approaches, achieving higher robustness to small dataset and cross-domain denoising. First, a sparse neighborhood graph is built from the output of a convolutional neural network (CNN). Then the image is restored by solving an unconstrained quadratic programming problem, using a corresponding graph Laplacian regularizer as a prior term. The proposed restoration pipeline is fully differentiable and hence can be end-to-end trained. Experimental results demonstrate that our work avoids overfitting given small training data. It is also endowed with strong cross-domain generalization power, outperforming the state-of-the-art approaches by remarkable margin.

##### Abstract (translated by Google)
我们建议结合基于模型的方法的稳健性优点和数据驱动的图像恢复方法的学习能力。具体而言，通过将图拉普拉斯正则化作为可训练模块集成到深度学习框架中，我们比纯CNN方法更不容易过度拟合，从而实现对小数据集和跨域去噪的更高鲁棒性。首先，从卷积神经网络（CNN）的输出构建稀疏邻域图。然后通过使用相应的图拉普拉斯正则化器作为先验项求解无约束二次规划问题来恢复图像。拟议的恢复管道是完全可区分的，因此可以进行端到端的训练。实验结果表明，我们的工作避免了过度拟合给定的小训练数据。它还具有强大的跨领域泛化能力，以卓越的优势超越了最先进的方法。

##### URL
[http://arxiv.org/abs/1807.11637](http://arxiv.org/abs/1807.11637)

##### PDF
[http://arxiv.org/pdf/1807.11637](http://arxiv.org/pdf/1807.11637)

