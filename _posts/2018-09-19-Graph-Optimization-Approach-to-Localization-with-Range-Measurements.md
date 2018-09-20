---
layout: post
title: "Graph Optimization Approach to Localization with Range Measurements"
date: 2018-09-19 06:18:57
categories: arXiv_RO
tags: arXiv_RO Drone Optimization
author: Xu Fang, Chen Wang, Thien-Minh Nguyen, Lihua Xie
mathjax: true
---

* content
{:toc}

##### Abstract
A range-based localization system is proposed based on graph optimization with ultra-wideband (UWB) measurements. There are still multiple issues for existing algorithms to be applied directly in real-time low power systems, especially for micro drones. For instance, the accuracy of triangularization is relatively low since it neglects the time differences of measured distances for position calculation. The filtering methods such as extended Kalman filter (EKF) are sensitive to measurement outliers and need accurate kinetic model. The machine learning methods are computational expensive and performance is unstable in different environments. To overcome the above problems, we propose to construct a joint trajectory smoothness and range constraint in a pose graph, which estimates robot poses over a sliding trajectory window at a single time instant. This removes the dependence on kinetic model and makes the system flexible and portable. Our algorithm is robust to outliers and even short-term measurement loss yet still with very low complexity. Extensive experiments under a variety of scenarios verify its stability and demonstrate a much higher accuracy than existing methods, especially in the attitude direction, which is challenging for existing methods due to an asymmetrical anchor distribution.

##### Abstract (translated by Google)
基于具有超宽带（UWB）测量的图优化，提出了基于范围的定位系统。现有算法仍然存在多个问题，直接应用于实时低功率系统，特别是对于微型无人机。例如，三角化的准确性相对较低，因为它忽略了测量距离的时间差来进行位置计算。扩展卡尔曼滤波器（EKF）等滤波方法对测量异常值敏感，需要精确的动力学模型。机器学习方法计算量大，并且在不同环境中性能不稳定。为了克服上述问题，我们提出在姿势图中构建关节轨迹平滑度和距离约束，其在单个时刻在滑动轨迹窗口上估计机器人姿态。这消除了对动力学模型的依赖，并使系统灵活和便携。我们的算法对异常值甚至短期测量损失都很稳健，但仍然具有非常低的复杂度。在各种情况下的大量实验验证了其稳定性并且表现出比现有方法高得多的精度，尤其是在姿态方向上，由于不对称的锚分布，这对现有方法具有挑战性。

##### URL
[http://arxiv.org/abs/1802.10276](http://arxiv.org/abs/1802.10276)

##### PDF
[http://arxiv.org/pdf/1802.10276](http://arxiv.org/pdf/1802.10276)

