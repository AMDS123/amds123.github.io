---
layout: post
title: "Resilient Active Target Tracking with Multiple Robots"
date: 2018-09-11 17:00:02
categories: arXiv_RO
tags: arXiv_RO Adversarial Tracking
author: Lifeng Zhou, Vasileios Tzoumas, George J. Pappas, Pratap Tokekar
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of target tracking with multiple robots consists of actively planning the motion of the robots to track the targets. A major challenge for practical deployments is to make the robots resilient to failures. In particular, robots may be attacked in adversarial scenarios, or their sensors may fail or get occluded. In this paper, we introduce planning algorithms for multi-target tracking that are resilient to such failures. In general, resilient target tracking is computationally hard. Contrary to the case where there are no failures, no scalable approximation algorithms are known for resilient target tracking when the targets are indistinguishable, or unknown in number, or with unknown motion model. In this paper we provide the first such algorithm, that also has the following properties: First, it achieves maximal resiliency, since the algorithm is valid for any number of failures. Second, it is scalable, as our algorithm terminates with the same running time as state-of-the-art algorithms for (non-resilient) target tracking. Third, it provides provable approximation bounds on the tracking performance, since our algorithm guarantees a solution that is guaranteed to be close to the optimal. We quantify our algorithm's approximation performance using a novel notion of curvature for monotone set functions subject to matroid constraints. Finally, we demonstrate the efficacy of our algorithm through MATLAB and Gazebo simulations, and a sensitivity analysis; we focus on scenarios that involve a known number of distinguishable targets.

##### Abstract (translated by Google)
使用多个机器人进行目标跟踪的问题包括主动规划机器人的运动以跟踪目标。实际部署的一个主要挑战是使机器人能够适应故障。特别是，机器人可能会在对抗场景中受到攻击，或者他们的传感器可能会失败或被遮挡。在本文中，我们介绍了针对此类故障具有弹性的多目标跟踪规划算法。通常，弹性目标跟踪在计算上很难。与没有故障的情况相反，当目标无法区分或数量未知或未知运动模型时，没有可伸缩近似算法用于弹性目标跟踪。在本文中，我们提供了第一个这样的算法，它还具有以下特性：首先，它实现了最大的弹性，因为该算法对于任何数量的故障都是有效的。其次，它是可扩展的，因为我们的算法终止的运行时间与（非弹性）目标跟踪的最新算法相同。第三，它为跟踪性能提供了可证明的近似界限，因为我们的算法保证了一个保证接近最优的解决方案。我们使用一个新的曲率概念来量化我们的算法的近似性能，这些概念用于受到拟阵约束的单调集函数。最后，我们通过MATLAB和Gazebo仿真证明了算法的有效性，并进行了灵敏度分析;我们专注于涉及已知数量的可区分目标的场景。

##### URL
[http://arxiv.org/abs/1809.04032](http://arxiv.org/abs/1809.04032)

##### PDF
[http://arxiv.org/pdf/1809.04032](http://arxiv.org/pdf/1809.04032)

