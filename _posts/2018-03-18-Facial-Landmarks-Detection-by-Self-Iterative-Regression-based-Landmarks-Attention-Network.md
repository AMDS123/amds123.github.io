---
layout: post
title: "Facial Landmarks Detection by Self-Iterative Regression based Landmarks-Attention Network"
date: 2018-03-18 03:32:35
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Detection Gradient_Descent
author: Tao Hu, Honggang Qi, Jizheng Xu, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Cascaded Regression (CR) based methods have been proposed to solve facial landmarks detection problem, which learn a series of descent directions by multiple cascaded regressors separately trained in coarse and fine stages. They outperform the traditional gradient descent based methods in both accuracy and running speed. However, cascaded regression is not robust enough because each regressor's training data comes from the output of previous regressor. Moreover, training multiple regressors requires lots of computing resources, especially for deep learning based methods. In this paper, we develop a Self-Iterative Regression (SIR) framework to improve the model efficiency. Only one self-iterative regressor is trained to learn the descent directions for samples from coarse stages to fine stages, and parameters are iteratively updated by the same regressor. Specifically, we proposed Landmarks-Attention Network (LAN) as our regressor, which concurrently learns features around each landmark and obtains the holistic location increment. By doing so, not only the rest of regressors are removed to simplify the training process, but the number of model parameters is significantly decreased. The experiments demonstrate that with only 3.72M model parameters, our proposed method achieves the state-of-the-art performance.

##### Abstract (translated by Google)
已提出基于级联回归（CR）的方法来解决面部标志检测问题，该方法通过在粗级和精级分别训练的多级级联回归器学习一系列下降方向。它们在精度和运行速度上都优于传统的基于梯度下降的方法。然而，级联回归不够稳健，因为每个回归者的训练数据来自先前回归器的输出。此外，训练多个回归器需要大量计算资源，特别是对于基于深度学习的方法。在本文中，我们开发了一个自我迭代回归（SIR）框架来提高模型效率。只有一个自我迭代回归器被训练以学习从粗级到精级的样本的下降方向，并且参数由同一个回归器迭代地更新。具体而言，我们提出了地标注意网络（LAN）作为我们的回归器，它同时学习每个地标附近的特征并获得整体位置增量。通过这样做，不仅其余的回归器被移除以简化训练过程，但是模型参数的数量显着减少。实验证明，只有3.72M模型参数，我们提出的方法达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1803.06598](https://arxiv.org/abs/1803.06598)

##### PDF
[https://arxiv.org/pdf/1803.06598](https://arxiv.org/pdf/1803.06598)

