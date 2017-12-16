---
layout: post
title: "Data-Driven Sparse Structure Selection for Deep Neural Networks"
date: 2017-07-05 05:21:50
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Knowledge CNN Optimization
author: Zehao Huang, Naiyan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks have liberated its extraordinary power on various tasks. However, it is still very challenging to deploy state-of-the-art models into real-world applications due to their high computational complexity. How can we design a compact and effective network without massive experiments and expert knowledge? In this paper, we propose a simple and effective framework to learn and prune deep models in an end-to-end manner. In our framework, a new type of parameter -- scaling factor is first introduced to scale the outputs of specific structures, such as neurons, groups or residual blocks. Then we add sparsity regularizations on these factors, and solve this optimization problem by a modified stochastic Accelerated Proximal Gradient (APG) method. By forcing some of the factors to zero, we can safely remove the corresponding structures, thus prune the unimportant parts of a CNN. Compared with other structure selection methods that may need thousands of trials or iterative fine-tuning, our method is trained fully end-to-end in one training pass without bells and whistles. We evaluate our method, Sparse Structure Selection with two state-of-the-art CNNs ResNet and ResNeXt, and demonstrate very promising results with adaptive depth and width selection.

##### Abstract (translated by Google)
深卷积神经网络在各种任务中解放了其非凡的力量。然而，由于计算复杂度高，将最先进的模型部署到实际应用中仍然是非常具有挑战性的。如何在没有大量实验和专业知识的情况下设计一个紧凑而有效的网络？在本文中，我们提出了一个简单而有效的框架，以端到端的方式学习和修剪深层模型。在我们的框架中，首先引入了一种新的参数 - 比例因子来缩放特定结构的输出，比如神经元，组或者残余块。然后在这些因子上增加稀疏正则化，并用修正的随机加速近似梯度（APG）方法求解这个优化问题。通过迫使一些因素归零，我们可以安全地移除相应的结构，从而修剪CNN的不重要的部分。与其他可能需要数千次试验或迭代微调的结构选择方法相比，我们的方法在一次训练中完全端对端地训练，没有任何的哨声。我们使用两个最先进的CNN ResNet和ResNeXt评估了我们的方法，稀疏结构选择，并展示了具有自适应深度和宽度选择的非常有前途的结果。

##### URL
[https://arxiv.org/abs/1707.01213](https://arxiv.org/abs/1707.01213)

##### PDF
[https://arxiv.org/pdf/1707.01213](https://arxiv.org/pdf/1707.01213)

