---
layout: post
title: "Extremely Low Bit Neural Network: Squeeze the Last Bit Out with ADMM"
date: 2017-09-13 03:21:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Deep_Learning Detection Recognition
author: Cong Leng, Hao Li, Shenghuo Zhu, Rong Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep learning models are highly effective for various learning tasks, their high computational costs prohibit the deployment to scenarios where either memory or computational resources are limited. In this paper, we focus on compressing and accelerating deep models with network weights represented by very small numbers of bits, referred to as extremely low bit neural network. We model this problem as a discretely constrained optimization problem. Borrowing the idea from Alternating Direction Method of Multipliers (ADMM), we decouple the continuous parameters from the discrete constraints of network, and cast the original hard problem into several subproblems. We propose to solve these subproblems using extragradient and iterative quantization algorithms that lead to considerably faster convergency compared to conventional optimization methods. Extensive experiments on image recognition and object detection verify that the proposed algorithm is more effective than state-of-the-art approaches when coming to extremely low bit neural network.

##### Abstract (translated by Google)
尽管深度学习模型对于各种学习任务是非常有效的，但是其高计算成本阻碍了部署到内存或计算资源有限的情况。在本文中，我们关注压缩和加速深度模型，网络权重以很小的比特数表示，称为极低位神经网络。我们将这个问题建模为一个离散约束优化问题。借鉴交替方向乘子法（ADMM）的思想，将连续参数从网络的离散约束中解耦出来，将原来的难题转化为几个子问题。我们建议使用额外的梯度和迭代量化算法来解决这些子问题，与传统的优化方法相比，这会导致更快的收敛性。在图像识别和目标检测方面进行了大量的实验，验证了该算法在进入极低位神经网络时比现有技术更有效。

##### URL
[https://arxiv.org/abs/1707.09870](https://arxiv.org/abs/1707.09870)

##### PDF
[https://arxiv.org/pdf/1707.09870](https://arxiv.org/pdf/1707.09870)

