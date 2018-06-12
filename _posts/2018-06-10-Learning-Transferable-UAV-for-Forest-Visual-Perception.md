---
layout: post
title: "Learning Transferable UAV for Forest Visual Perception"
date: 2018-06-10 10:15:40
categories: arXiv_RO
tags: arXiv_RO Classification
author: Lyujie Chen, Wufan Wang, Jihong Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new pipeline of training a monocular UAV to fly a collision-free trajectory along the dense forest trail. As gathering high-precision images in the real world is expensive and the off-the-shelf dataset has some deficiencies, we collect a new dense forest trail dataset in a variety of simulated environment in Unreal Engine. Then we formulate visual perception of forests as a classification problem. A ResNet-18 model is trained to decide the moving direction frame by frame. To transfer the learned strategy to the real world, we construct a ResNet-18 adaptation model via multi-kernel maximum mean discrepancies to leverage the relevant labelled data and alleviate the discrepancy between simulated and real environment. Simulation and real-world flight with a variety of appearance and environment changes are both tested. The ResNet-18 adaptation and its variant model achieve the best result of 84.08% accuracy in reality.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的管道，可以训练单眼无人机沿着茂密的森林小径飞行无碰撞轨迹。由于在真实世界中收集高精度图像的成本很高，而现成的数据集有一些缺陷，因此我们在虚幻引擎中的各种模拟环境中收集新的密集森林道数据集。然后我们将森林的视觉感知作为分类问题。 ResNet-18模型经过训练可逐帧决定移动方向。为了将学习策略转移到现实世界中，我们通过多内核最大均值差异构建ResNet-18自适应模型，以利用相关标记数据并减轻模拟和真实环境之间的差异。模拟和真实世界的飞行与各种外观和环境变化都进行了测试。 ResNet-18自适应及其变型模型在现实中达到了84.08％的最佳精度。

##### URL
[http://arxiv.org/abs/1806.03626](http://arxiv.org/abs/1806.03626)

##### PDF
[http://arxiv.org/pdf/1806.03626](http://arxiv.org/pdf/1806.03626)

