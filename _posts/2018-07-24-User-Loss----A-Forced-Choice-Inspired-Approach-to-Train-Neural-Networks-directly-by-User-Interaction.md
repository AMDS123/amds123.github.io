---
layout: post
title: "User Loss -- A Forced-Choice-Inspired Approach to Train Neural Networks directly by User Interaction"
date: 2018-07-24 18:43:36
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Shahab Zarei, Bernhard Stimpel, Christopher Syben, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate whether is it possible to train a neural network directly from user inputs. We consider this approach to be highly relevant for applications in which the point of optimality is not well-defined and user-dependent. Our application is medical image denoising which is essential in fluoroscopy imaging. In this field every user, i.e. physician, has a different flavor and image quality needs to be tailored towards each individual. 
 To address this important problem, we propose to construct a loss function derived from a forced-choice experiment. In order to make the learning problem feasible, we operate in the domain of precision learning, i.e., we inspire the network architecture by traditional signal processing methods in order to reduce the number of trainable parameters. The algorithm that was used for this is a Laplacian pyramid with only six trainable parameters. 
 In the experimental results, we demonstrate that two image experts who prefer different filter characteristics between sharpness and de-noising can be created using our approach. Also models trained for a specific user perform best on this users test data. This approach opens the way towards implementation of direct user feedback in deep learning and is applicable for a wide range of application.

##### Abstract (translated by Google)
在本文中，我们研究是否可以直接从用户输入训练神经网络。我们认为这种方法与最优点没有明确定义和用户相关的应用高度相关。我们的应用是医学图像去噪，这在荧光透视成像中是必不可少的。在该领域中，每个用户（即医生）具有不同的风味，并且需要针对每个个体定制图像质量。
 为了解决这个重要问题，我们建议构建一个源自强制选择实验的损失函数。为了使学习问题可行，我们在精确学习领域进行操作，即，我们通过传统的信号处理方法激励网络架构，以减少可训练参数的数量。用于此的算法是拉普拉斯金字塔，其仅具有六个可训练参数。
 在实验结果中，我们证明了使用我们的方法可以创建两个喜欢锐度和去噪之间不同滤波器特性的图像专家。此外，针对特定用户培训的模型在该用户测试数据上表现最佳。这种方法为在深度学习中实现直接用户反馈开辟了道路，适用于广泛的应用。

##### URL
[http://arxiv.org/abs/1807.09303](http://arxiv.org/abs/1807.09303)

##### PDF
[http://arxiv.org/pdf/1807.09303](http://arxiv.org/pdf/1807.09303)

