---
layout: post
title: "Multiple scan data association by convex variational inference"
date: 2018-01-23 22:57:39
categories: arXiv_AI
tags: arXiv_AI Tracking Inference
author: Jason L. Williams, Roslyn A. Lau
mathjax: true
---

* content
{:toc}

##### Abstract
Data association, the reasoning over correspondence between targets and measurements, is a problem of fundamental importance in target tracking. Recently, belief propagation (BP) has emerged as a promising method for estimating the marginal probabilities of measurement to target association, providing fast, accurate estimates. The excellent performance of BP in the particular formulation used may be attributed to the convexity of the underlying free energy which it implicitly optimises. This paper studies multiple scan data association problems, i.e., problems that reason over correspondence between targets and several sets of measurements, which may correspond to different sensors or different time steps. We find that the multiple scan extension of the single scan BP formulation is non-convex and demonstrate the undesirable behaviour that can result. A convex free energy is constructed using the recently proposed fractional free energy (FFE). A convergent, BP-like algorithm is provided for the single scan FFE, and employed in optimising the multiple scan free energy using primal-dual coordinate ascent. Finally, based on a variational interpretation of joint probabilistic data association (JPDA), we develop a sequential variant of the algorithm that is similar to JPDA, but retains consistency constraints from prior scans. The performance of the proposed methods is demonstrated on a bearings only target localisation problem.

##### Abstract (translated by Google)
数据关联是目标跟测量之间对应关系的推理，是目标跟踪的根本重要问题。最近，信度传播（BP）已经成为一种有前途的方法来估计测量对目标关联的边际概率，从而提供快速，准确的估计。 BP在所使用的特定配方中的优异性能可能归因于其隐含优化的基本自由能的凸性。本文研究了多个扫描数据关联问题，即目标与多组测量之间的对应关系的问题，这些测量可能对应于不同的传感器或不同的时间步长。我们发现单次扫描BP公式的多重扫描扩展是非凸的，并且证明了可能导致的不良行为。使用最近提出的分数自由能（FFE）构造凸自由能。为单次扫描FFE提供了一种类似BP的算法，用于利用原始 - 双重坐标上升对多次扫描自由能进行优化。最后，基于对联合概率数据关联（JPDA）的变化解释，我们开发了与JPDA类似的算法的顺序变体，但是保留了来自先前扫描的一致性约束。所提出的方法的性能表现在仅有轴承的目标定位问题上。

##### URL
[http://arxiv.org/abs/1607.07942](http://arxiv.org/abs/1607.07942)

##### PDF
[http://arxiv.org/pdf/1607.07942](http://arxiv.org/pdf/1607.07942)

