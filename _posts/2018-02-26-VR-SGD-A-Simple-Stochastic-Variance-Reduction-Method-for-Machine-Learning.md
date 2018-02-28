---
layout: post
title: "VR-SGD: A Simple Stochastic Variance Reduction Method for Machine Learning"
date: 2018-02-26 12:56:07
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Fanhua Shang, Kaiwen Zhou, James Cheng, Ivor W. Tsang, Lijun Zhang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple variant of the original SVRG, called variance reduced stochastic gradient descent (VR-SGD). Unlike the choices of snapshot and starting points in SVRG and its proximal variant, Prox-SVRG, the two vectors of VR-SGD are set to the average and last iterate of the previous epoch, respectively. The settings allow us to use much larger learning rates, and also make our convergence analysis more challenging. We also design two different update rules for smooth and non-smooth objective functions, respectively, which means that VR-SGD can tackle non-smooth and/or non-strongly convex problems directly without any reduction techniques. Moreover, we analyze the convergence properties of VR-SGD for strongly convex problems, which show that VR-SGD attains linear convergence. Different from its counterparts that have no convergence guarantees for non-strongly convex problems, we also provide the convergence guarantees of VR-SGD for this case, and empirically verify that VR-SGD with varying learning rates achieves similar performance to its momentum accelerated variant that has the optimal convergence rate $\mathcal{O}(1/T^2)$. Finally, we apply VR-SGD to solve various machine learning problems, such as convex and non-convex empirical risk minimization, leading eigenvalue computation, and neural networks. Experimental results show that VR-SGD converges significantly faster than SVRG and Prox-SVRG, and usually outperforms state-of-the-art accelerated methods, e.g., Katyusha.

##### Abstract (translated by Google)
在本文中，我们提出了原始SVRG的简单变体，称为方差降低随机梯度下降（VR-SGD）。与SVRG及其近似变体Prox-SVRG中的快照和起始点的选择不同，VR-SGD的两个向量分别设置为前一个历元的平均和最后一次迭代。这些设置使我们能够使用更大的学习率，并使我们的收敛分析更具挑战性。我们还分别为平滑和非平滑目标函数设计了两种不同的更新规则，这意味着VR-SGD可以直接处理非光滑和/或非强凸问题而无需任何还原技术。此外，我们分析了VR-SGD对于强凸问题的收敛性，表明VR-SGD达到线性收敛。与那些对非强凸问题没有收敛保证的对应方不同，我们也为这种情况提供了VR-SGD的收敛性保证，并且凭经验验证具有不同学习速率的VR-SGD实现了与其动量加速变体类似的性能具有最优收敛速度$ \ mathcal {O}（1 / T ^ 2）$。最后，我们应用VR-SGD来解决各种机器学习问题，如凸和非凸经验风险最小化，主要特征值计算和神经网络。实验结果表明，VR-SGD收敛速度明显快于SVRG和Prox-SVRG，并且通常优于现有技术的加速方法，例如Katyusha。

##### URL
[https://arxiv.org/abs/1802.09932](https://arxiv.org/abs/1802.09932)

##### PDF
[https://arxiv.org/pdf/1802.09932](https://arxiv.org/pdf/1802.09932)

