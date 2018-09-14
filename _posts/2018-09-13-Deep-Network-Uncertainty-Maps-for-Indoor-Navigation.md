---
layout: post
title: "Deep Network Uncertainty Maps for Indoor Navigation"
date: 2018-09-13 11:33:32
categories: arXiv_RO
tags: arXiv_RO Face CNN Prediction
author: Jens Lundell, Francesco Verdoja, Ville Kyrki
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the uncertainty of predictions is a crucial ability for robots in unstructured environments. Most mobile robots for indoor use rely on 2D laser scanners for localization, mapping and navigation. These sensors, however, cannot detect transparent surfaces or measure the full occupancy of complex objects such as tables. Deep Neural Networks have recently been proposed to overcome this limitation by learning to estimate object occupancy. These estimates are nevertheless subject to noise, making the evaluation of their confidence an important issue. In this work we study uncertainty estimation in deep models, proposing a novel solution based on a fully convolutional autoencoder. The proposed architecture is not restricted by the assumption that the uncertainty follows a Gaussian model, as in the case of many popular solutions for deep model uncertainty estimation, e.g., MC Dropout. We present results showing that uncertainty over obstacle distances is actually better modeled with a Laplace distribution. As an example of application where uncertainty evaluation is crucial, we also present an algorithm to build a map that includes information over obstacle distance estimates while taking into account the level of uncertainty in each estimate. We finally show how the constructed map can be used to increase global navigation safety by planning trajectories which avoid areas of high uncertainty, enabling higher autonomy for mobile robots in indoor settings.

##### Abstract (translated by Google)
估计预测的不确定性是机器人在非结构化环境中的关键能力。大多数室内使用的移动机器人依靠2D激光扫描仪进行定位，绘图和导航。但是，这些传感器无法检测透明表面或测量复杂对象（如表格）的完全占用情况。最近已提出深度神经网络通过学习估计物体占用来克服该限制。然而，这些估计值受到噪音影响，因此评估其信心是一个重要问题。在这项工作中，我们研究深度模型中的不确定性估计，提出了一种基于完全卷积自动编码器的新颖解决方案。所提出的架构不受不确定性遵循高斯模型的假设的限制，如用于深度模型不确定性估计的许多流行解决方案的情况，例如MC Dropout。我们提出的结果表明，障碍物距离的不确定性实际上更好地用拉普拉斯分布建模。作为不确定性评估至关重要的应用示例，我们还提出了一种算法，用于构建包含障碍物距离估计信息的地图，同时考虑每个估计的不确定性水平。我们最终展示了如何通过规划轨迹来提高全球导航安全性，从而避免高度不确定的区域，从而为室内环境中的移动机器人提供更高的自主权。

##### URL
[http://arxiv.org/abs/1809.04891](http://arxiv.org/abs/1809.04891)

##### PDF
[http://arxiv.org/pdf/1809.04891](http://arxiv.org/pdf/1809.04891)

