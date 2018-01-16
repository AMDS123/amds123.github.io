---
layout: post
title: "A Scalable Belief Propagation Algorithm for Radio Signal Based SLAM"
date: 2018-01-13 16:24:02
categories: arXiv_RO
tags: arXiv_RO Face SLAM
author: Erik Leitinger, Florian Meyer, Franz Hlawatsch, Klaus Witrisal, Fredrik Tufvesson, Moe Z. Win
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simultaneous localization and mapping (SLAM) algorithm that is based on radio signals and the association of specular multipath components (MPCs) with geometric features. Especially in indoor scenarios, localization from radio signals is challenging due to diffuse multipath propagation and the unknown MPC-featureassociation. In our approach, specular reflections at flat surfaces (e.g., walls) are described in terms of virtual anchors (VAs). The positions of these VAs are unknown and possibly time-varying. We develop a Bayesian model of the SLAM problem including the unknown MPC-VA association. We represent this model by a factor graph, which enables the use of the belief propagation (BP) scheme for efficient marginalization of the joint posterior distribution. The resulting BP-based SLAM algorithm detects the VAs and estimates the time-varying position of the mobile agent and the possibly time-varying positions of the VAs, thereby leveraging the MPCs in the radio signal for improved accuracy and robustness of agent localization. A core aspect of the algorithm is BP-based probabilistic MPC-VA association. Moreover, for improved initialization of new VA positions, the states of unobserved potential VAs are modeled as a random finite set and propagated in time by means of a "zero-measurement" probability hypothesis density filter. The proposed BP-based SLAM algorithm has a low computational complexity and scales well in all relevant system parameters. Experimental results using both synthetically generated measurements and realultra-wideband radio signals demonstrate the excellent performance of the algorithm in challenging indoor environments.

##### Abstract (translated by Google)
我们提出了一种基于无线电信号的同时定位和映射（SLAM）算法，以及镜面多径分量（MPC）与几何特征的关联。特别是在室内场景中，由于漫射多径传播和未知的MPC特征关联，无线电信号的定位是具有挑战性的。在我们的方法中，平面（例如，墙壁）上的镜面反射用虚拟锚（VAs）来描述。这些VA的位置是未知的，可能是随时间变化的。我们开发了SLAM问题的贝叶斯模型，包括未知的MPC-VA关联。我们用一个因子图来表示这个模型，这使得能够使用信念传播（BP）方案来对联合后验分布进行有效的边缘化。由此产生的基于BP的SLAM算法检测VA并估计移动代理的时变位置和VA的可能随时间变化的位置，从而利用无线电信号中的MPC来提高代理定位的准确性和鲁棒性。该算法的核心部分是基于BP的概率MPC-VA关联。此外，为了改善新的VA位置的初始化，将未观察到的电位VA的状态建模为随机有限集合，并通过“零测量”概率假设密度滤波器及时传播。所提出的基于BP的SLAM算法具有较低的计算复杂度，并且在所有相关的系统参数中都能很好地扩展。使用综合生成的测量和realultra宽带无线电信号的实验结果表明该算法在挑战室内环境中的出色性能。

##### URL
[http://arxiv.org/abs/1801.04463](http://arxiv.org/abs/1801.04463)

##### PDF
[http://arxiv.org/pdf/1801.04463](http://arxiv.org/pdf/1801.04463)

