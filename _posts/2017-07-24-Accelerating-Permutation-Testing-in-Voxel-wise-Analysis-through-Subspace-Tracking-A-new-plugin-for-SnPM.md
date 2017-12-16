---
layout: post
title: "Accelerating Permutation Testing in Voxel-wise Analysis through Subspace Tracking: A new plugin for SnPM"
date: 2017-07-24 18:03:54
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Felipe Gutierrez-Barragan, Vamsi K. Ithapu, Chris Hinrichs, Camille Maumet, Sterling C. Johnson, Thomas E. Nichols, Vikas Singh, the ADNI
mathjax: true
---

* content
{:toc}

##### Abstract
Permutation testing is a non-parametric method for obtaining the max null distribution used to compute corrected $p$-values that provide strong control of false positives. In neuroimaging, however, the computational burden of running such an algorithm can be significant. We find that by viewing the permutation testing procedure as the construction of a very large permutation testing matrix, $T$, one can exploit structural properties derived from the data and the test statistics to reduce the runtime under certain conditions. In particular, we see that $T$ is low-rank plus a low-variance residual. This makes $T$ a good candidate for low-rank matrix completion, where only a very small number of entries of $T$ ($\sim0.35\%$ of all entries in our experiments) have to be computed to obtain a good estimate. Based on this observation, we present RapidPT, an algorithm that efficiently recovers the max null distribution commonly obtained through regular permutation testing in voxel-wise analysis. We present an extensive validation on a synthetic dataset and four varying sized datasets against two baselines: Statistical NonParametric Mapping (SnPM13) and a standard permutation testing implementation (referred as NaivePT). We find that RapidPT achieves its best runtime performance on medium sized datasets ($50 \leq n \leq 200$), with speedups of 1.5x - 38x (vs. SnPM13) and 20x-1000x (vs. NaivePT). For larger datasets ($n \geq 200$) RapidPT outperforms NaivePT (6x - 200x) on all datasets, and provides large speedups over SnPM13 when more than 10000 permutations (2x - 15x) are needed. The implementation is a standalone toolbox and also integrated within SnPM13, able to leverage multi-core architectures when available.

##### Abstract (translated by Google)
置换测试是获得最大零分布的非参数方法，用于计算校正后的$ p $值，从而提供强烈的误报控制。然而，在神经影像学中，运行这种算法的计算负担可能是显着的。我们发现，通过将排列测试过程视为一个非常大的置换测试矩阵$ T $的构造，可以利用从数据和测试统计得到的结构属性来减少某些条件下的运行时间。特别是，我们看到$ T $是低阶加低方差残差。这使得$ T $成为低阶矩阵完成的一个很好的候选者，其中只有非常少量的$ T $（我们实验中所有条目）的条目必须被计算来获得好估计。基于这个观察，我们提出RapidPT，一种算法，可以有效地恢复在体素分析中通过常规置换测试通常获得的最大零分布。我们对合成数据集和四个不同大小的数据集进行了广泛验证，这两个数据集是针对两个基线：统计非参数映射（SnPM13）和标准置换测试实现（简称为NaivePT）。我们发现RapidPTF在中等大小的数据集（$ 50 \ leq n \ leq 200 $）上实现了最佳运行时性能，加速比为1.5x-38x（与SnPM13相比）和20x-1000x（与NaivePT相比）。对于较大的数据集（$ n \ geq 200 $），在所有数据集上，RapidPT优于NaivePT（6x  -  200x），并且在需要超过10000个排列（2x  -  15x）时，提供SnPM13上的大型加速。该实现是一个独立的工具箱，也集成在SnPM13中，可以利用多核架构。

##### URL
[https://arxiv.org/abs/1703.01506](https://arxiv.org/abs/1703.01506)

##### PDF
[https://arxiv.org/pdf/1703.01506](https://arxiv.org/pdf/1703.01506)

