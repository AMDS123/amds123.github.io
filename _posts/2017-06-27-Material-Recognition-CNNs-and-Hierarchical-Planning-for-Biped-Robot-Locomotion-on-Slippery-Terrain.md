---
layout: post
title: "Material Recognition CNNs and Hierarchical Planning for Biped Robot Locomotion on Slippery Terrain"
date: 2017-06-27 06:38:53
categories: arXiv_CV
tags: arXiv_CV Knowledge Face CNN Prediction Recognition
author: Martim Brandao, Yukitoshi Minami Shiguematsu, Kenji Hashimoto, Atsuo Takanishi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we tackle the problem of visually predicting surface friction for environments with diverse surfaces, and integrating this knowledge into biped robot locomotion planning. The problem is essential for autonomous robot locomotion since diverse surfaces with varying friction abound in the real world, from wood to ceramic tiles, grass or ice, which may cause difficulties or huge energy costs for robot locomotion if not considered. We propose to estimate friction and its uncertainty from visual estimation of material classes using convolutional neural networks, together with probability distribution functions of friction associated with each material. We then robustly integrate the friction predictions into a hierarchical (footstep and full-body) planning method using chance constraints, and optimize the same trajectory costs at both levels of the planning method for consistency. Our solution achieves fully autonomous perception and locomotion on slippery terrain, which considers not only friction and its uncertainty, but also collision, stability and trajectory cost. We show promising friction prediction results in real pictures of outdoor scenarios, and planning experiments on a real robot facing surfaces with different friction.

##### Abstract (translated by Google)
在本文中，我们解决了对具有不同表面的环境的表面摩擦进行视觉预测的问题，并将这些知识整合到双足机器人运动规划中。这个问题对于自主机器人的运动至关重要，因为在现实世界中，从木材到瓷砖，草地或者冰块，各种不同的摩擦表面都存在着不同的摩擦力，如果不考虑的话，这会给机器人的运动带来困难或者巨大的能源成本。我们建议使用卷积神经网络来估计材料类别的视觉估计中的摩擦及其不确定性，以及与每种材料相关的摩擦概率分布函数。然后，我们使用机会约束将摩擦预测强有力地整合到分层（足迹和全身）规划方法中，并在两个一致性规划方法的水平上优化相同的轨迹成本。我们的解决方案在湿滑的地形上实现了完全自主的感知和运动，不仅考虑到摩擦及其不确定性，还考虑了碰撞，稳定性和轨迹成本。我们展示了有希望的摩擦预测结果在户外场景的真实图片，并计划在真正的机器人面对不同的摩擦表面的实验。

##### URL
[https://arxiv.org/abs/1706.08685](https://arxiv.org/abs/1706.08685)

##### PDF
[https://arxiv.org/pdf/1706.08685](https://arxiv.org/pdf/1706.08685)

