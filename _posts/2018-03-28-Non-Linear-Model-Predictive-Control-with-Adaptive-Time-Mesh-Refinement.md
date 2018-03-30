---
layout: post
title: "Non-Linear Model Predictive Control with Adaptive Time-Mesh Refinement"
date: 2018-03-28 10:32:47
categories: arXiv_RO
tags: arXiv_RO
author: Ciro Potena, Bartolomeo Della Corte, Daniele Nardi, Giorgio Grisetti, Alberto Pretto
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel solution for real-time, Non-Linear Model Predictive Control (NMPC) exploiting a time-mesh refinement strategy. The proposed controller formulates the Optimal Control Problem (OCP) in terms of flat outputs over an adaptive lattice. In common approximated OCP solutions, the number of discretization points composing the lattice represents a critical upper bound for real-time applications. The proposed NMPC-based technique refines the initially uniform time horizon by adding time steps with a sampling criterion that aims to reduce the discretization error. This enables a higher accuracy in the initial part of the receding horizon, which is more relevant to NMPC, while keeping bounded the number of discretization points. By combining this feature with an efficient Least Square formulation, our solver is also extremely time-efficient, generating trajectories of multiple seconds within only a few milliseconds. The performance of the proposed approach has been validated in a high fidelity simulation environment, by using an UAV platform. We also released our implementation as open source C++ code.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的实时非线性模型预测控制（NMPC）解决方案，它利用时间网格细化策略。所提出的控制器根据自适应网格上的平坦输出来制定最优控制问题（OCP）。在常用的近似OCP解决方案中，组成网格的离散化点的数量代表了实时应用的关键上限。所提出的基于NMPC的技术通过增加时间步长和旨在减少离散误差的采样标准来优化最初统一的时间范围。这使得在与NMPC更相关的后退视界的初始部分中具有更高的准确性，同时保持离散点的数量有界。通过将此功能与高效的最小二乘公式相结合，我们的解算器也非常省时，在几毫秒内即可生成多秒的轨迹。所提出的方法的性能已经通过使用无人机平台在高保真模拟环境中验证。我们还以开源C ++代码的形式发布了我们的实现。

##### URL
[https://arxiv.org/abs/1803.10512](https://arxiv.org/abs/1803.10512)

##### PDF
[https://arxiv.org/pdf/1803.10512](https://arxiv.org/pdf/1803.10512)

