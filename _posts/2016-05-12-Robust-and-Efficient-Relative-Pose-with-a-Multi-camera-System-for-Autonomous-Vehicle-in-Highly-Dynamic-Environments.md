---
layout: post
title: "Robust and Efficient Relative Pose with a Multi-camera System for Autonomous Vehicle in Highly Dynamic Environments"
date: 2016-05-12 06:00:05
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Liu Liu, Hongdong Li, Yuchao Dai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the relative pose problem for autonomous vehicle driving in highly dynamic and possibly cluttered environments. This is a challenging scenario due to the existence of multiple, large, and independently moving objects in the environment, which often leads to excessive portion of outliers and results in erroneous motion estimation. Existing algorithms cannot cope with such situations well. This paper proposes a new algorithm for relative pose using a multi-camera system with multiple non-overlapping individual cameras. The method works robustly even when the numbers of outliers are overwhelming. By exploiting specific prior knowledge of driving scene we have developed an efficient 4-point algorithm for multi-camera relative pose, which admits analytic solutions by solving a polynomial root-finding equation, and runs extremely fast (at about 0.5$u$s per root). When the solver is used in combination with RANSAC, we are able to quickly prune unpromising hypotheses, significantly improve the chance of finding inliers. Experiments on synthetic data have validated the performance of the proposed algorithm. Tests on real data further confirm the method's practical relevance.

##### Abstract (translated by Google)
本文研究了在高度动态和可能的杂乱环境下自主驾驶的相对姿态问题。由于在环境中存在多个，大的和独立移动的物体，这是一个具有挑战性的情况，这经常导致过多的异常值部分并导致错误的运动估计。现有的算法不能很好地处理这种情况。本文提出了一种新的多摄像机系统相对姿态的算法，该系统具有多个不重叠的单个摄像机。该方法即使在异常数量非常大的情况下也能够稳健运行。通过利用驾驶场景的特定先验知识，我们开发了一种多摄像机相对姿态的有效4点算法，该算法通过求解多项式根发现方程来接受解析解，并且运行速度非常快（约为每秒0.5美元根）。当求解器与RANSAC结合使用时，我们能够快速修剪未经验证的假设，显着提高找到内点的机会。对合成数据的实验验证了所提算法的性能。对实际数据的测试进一步证实了该方法的实际相关性。

##### URL
[https://arxiv.org/abs/1605.03689](https://arxiv.org/abs/1605.03689)

##### PDF
[https://arxiv.org/pdf/1605.03689](https://arxiv.org/pdf/1605.03689)

