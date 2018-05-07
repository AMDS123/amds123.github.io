---
layout: post
title: "A Convex Approximation of the Relaxed Binaural Beamforming Optimization Problem"
date: 2018-05-04 10:01:56
categories: arXiv_SD
tags: arXiv_SD Optimization
author: Andreas I. Koutrouvelis, Richard C. Hendriks, Richard Heusdens, Jesper Jensen
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed relaxed binaural beamforming (RBB) optimization problem provides a flexible trade-off between noise suppression and binaural-cue preservation of the sound sources in the acoustic scene. It minimizes the output noise power, under the constraints which guarantee that the target remains unchanged after processing and the binaural-cue distortions of the acoustic sources will be less than a user-defined threshold. However, the RBB problem is a computationally demanding non-convex optimization problem. The only existing suboptimal method which approximately solves the RBB is a successive convex optimization (SCO) method which, typically, requires to solve multiple convex optimization problems per frequency bin, in order to converge. Convergence is achieved when all constraints of the RBB optimization problem are satisfied. In this paper, we propose a semi-definite convex relaxation (SDCR) of the RBB optimization problem. The proposed suboptimal SDCR method solves a single convex optimization problem per frequency bin, resulting in a much lower computational complexity than the SCO method. Unlike the SCO method, the SDCR method does not guarantee user-controlled upper-bounded binaural-cue distortions. To tackle this problem we also propose a suboptimal hybrid method which combines the SDCR and SCO methods. Instrumental measures combined with a listening test show that the SDCR and hybrid methods achieve significantly lower computational complexity than the SCO method, and in most cases better trade-off between predicted intelligibility and binaural-cue preservation than the SCO method.

##### Abstract (translated by Google)
最近提出的放松双耳波束形成（RBB）优化问题在噪声抑制和声场中的声源的双耳线索保存之间提供了灵活的折衷。它在保证目标在处理后保持不变并且声源的双耳线索失真小于用户定义的阈值的约束条件下使输出噪声功率最小化。然而，RBB问题是一个计算要求非凸优化问题。近似解决RBB的唯一存在的次优方法是连续凸优化（SCO）方法，其通常需要解决每个频率箱的多个凸优化问题以便收敛。收敛是在满足RBB优化问题的所有约束时实现的。在本文中，我们提出了RBB优化问题的半定凸松弛（SDCR）。所提出的次优SDCR方法针对每个频率仓求解单凸优化问题，导致比SCO方法低得多的计算复杂度。与SCO方法不同，SDCR方法不保证用户控制的上限双耳线索失真。为了解决这个问题，我们还提出了一种结合了SDCR和SCO方法的次优混合方法。器乐测量结合听力测试表明，与SCO方法相比，SDCR和混合方法的计算复杂度显着降低，并且在大多数情况下，预测可懂度和双耳线索保存之间的折衷比SCO方法更好。

##### URL
[http://arxiv.org/abs/1805.01692](http://arxiv.org/abs/1805.01692)

##### PDF
[http://arxiv.org/pdf/1805.01692](http://arxiv.org/pdf/1805.01692)

