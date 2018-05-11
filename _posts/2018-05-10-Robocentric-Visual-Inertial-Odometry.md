---
layout: post
title: "Robocentric Visual-Inertial Odometry"
date: 2018-05-10 15:56:08
categories: arXiv_RO
tags: arXiv_RO Tracking
author: Zheng Huai, Guoquan Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel robocentric formulation of the visual-inertial navigation system (VINS) within a sliding-window filtering framework and design an efficient, lightweight, robocentric visual-inertial odometry (R-VIO) algorithm for consistent motion tracking even in challenging environments using only a monocular camera and a 6-axis IMU. The key idea is to deliberately reformulate the VINS with respect to a moving local frame, rather than a fixed global frame of reference as in the standard world-centric VINS, in order to obtain relative motion estimates of higher accuracy for updating global poses. As an immediate advantage of this robocentric formulation, the proposed R-VIO can start from an arbitrary pose, without the need to align the initial orientation with the global gravitational direction. More importantly, we analytically show that the linearized robocentric VINS does not undergo the observability mismatch issue as in the standard world-centric counterpart which was identified in the literature as the main cause of estimation inconsistency. Additionally, we investigate in-depth the special motions that degrade the performance in the world-centric formulation and show that such degenerate cases can be easily compensated in the proposed robocentric formulation, without resorting to additional sensors as in the world-centric formulation, thus leading to better robustness. The proposed R-VIO algorithm has been extensively tested through both Monte Carlo simulations and real-world experiments with different sensor platforms navigating in different environments, and shown to achieve better (or competitive at least) performance than the state-of-the-art VINS, in terms of consistency, accuracy and efficiency.

##### Abstract (translated by Google)
在本文中，我们提出了一种在滑动窗过滤框架内的视觉 - 惯性导航系统（VINS）的新型机器人中心公式，并设计了一种高效，轻便，以机器人为中心的视觉惯性测距（R-VIO）算法，以实现一致的运动跟踪在仅使用单眼相机和6轴IMU的具有挑战性的环境中。关键思想是有意识地将VINS重新定位为移动的局部框架，而不是像标准的以世界为中心的VINS那样的固定的全局参考框架，以便获得用于更新全局姿势的更高准确度的相对运动估计。作为这种robocentric公式的直接优势，所提出的R-VIO可以从任意姿态开始，而不需要将初始方向与全局重力方向对齐。更重要的是，我们通过分析表明，线性化的机器人中心VINS不会像在标准的以世界为中心的标准中那样遭受可观测性不匹配问题，这在文献中被认为是估计不一致的主要原因。此外，我们深入研究了以世界为中心的公式中降低性能的特殊运动，并表明这种退化情况可以在拟议的机器人中心公式中轻松补偿，而不需要像以世界为中心的公式那样采用额外的传感器，因此导致更好的健壮性。所提出的R-VIO算法已经通过蒙特卡罗模拟和使用不同传感器平台在不同环境中导航的实际实验进行了广泛的测试，并且显示出比现有技术更好（或至少具有竞争性）的性能VINS，在一致性，准确性和效率方面。

##### URL
[http://arxiv.org/abs/1805.04031](http://arxiv.org/abs/1805.04031)

##### PDF
[http://arxiv.org/pdf/1805.04031](http://arxiv.org/pdf/1805.04031)

