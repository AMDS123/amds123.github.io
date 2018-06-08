---
layout: post
title: "Gaussian Mixture Reduction for Time-Constrained Approximate Inference in Hybrid Bayesian Networks"
date: 2018-06-06 20:38:27
categories: arXiv_AI
tags: arXiv_AI Image_Caption Inference Detection
author: Cheol Young Park, Kathryn Blackmond Laskey, Paulo C. G. Costa, Shou Matsumoto
mathjax: true
---

* content
{:toc}

##### Abstract
Hybrid Bayesian Networks (HBNs), which contain both discrete and continuous variables, arise naturally in many application areas (e.g., image understanding, data fusion, medical diagnosis, fraud detection). This paper concerns inference in an important subclass of HBNs, the conditional Gaussian (CG) networks, in which all continuous random variables have Gaussian distributions and all children of continuous random variables must be continuous. Inference in CG networks can be NP-hard even for special-case structures, such as poly-trees, where inference in discrete Bayesian networks can be performed in polynomial time. Therefore, approximate inference is required. In approximate inference, it is often necessary to trade off accuracy against solution time. This paper presents an extension to the Hybrid Message Passing inference algorithm for general CG networks and an algorithm for optimizing its accuracy given a bound on computation time. The extended algorithm uses Gaussian mixture reduction to prevent an exponential increase in the number of Gaussian mixture components. The trade-off algorithm performs pre-processing to find optimal run-time settings for the extended algorithm. Experimental results for four CG networks compare performance of the extended algorithm with existing algorithms and show the optimal settings for these CG networks.

##### Abstract (translated by Google)
包含离散和连续变量的混合贝叶斯网络（HBN）在许多应用领域（例如图像理解，数据融合，医学诊断，欺诈检测）中自然产生。本文关注HBNs的一个重要子类，条件高斯（CG）网络中的推理，其中所有连续随机变量具有高斯分布，并且所有连续随机变量的子必须是连续的。 CG网络中的推论即使对于特殊情况的结构（如多树）也可能是NP难的，在这种情况下，可以在多项式时间内执行离散贝叶斯网络中的推理。因此，需要进行近似推理。在近似推理中，通常有必要对解决时间进行权衡。本文提出了针对通用CG网络的混合消息传递推理算法的扩展，并给出了计算时间约束条件下优化其精度的算法。扩展算法使用高斯混合减少来防止高斯混合分量数量的指数增加。权衡算法执行预处理以找到扩展算法的最佳运行时间设置。四个CG网络的实验结果将扩展算法的性能与现有算法进行比较，并显示这些CG网络的最佳设置。

##### URL
[http://arxiv.org/abs/1806.02415](http://arxiv.org/abs/1806.02415)

##### PDF
[http://arxiv.org/pdf/1806.02415](http://arxiv.org/pdf/1806.02415)

