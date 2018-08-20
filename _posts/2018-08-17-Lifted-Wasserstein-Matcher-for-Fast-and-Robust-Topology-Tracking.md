---
layout: post
title: "Lifted Wasserstein Matcher for Fast and Robust Topology Tracking"
date: 2018-08-17 13:54:05
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Maxime Soler, M&#xe9;lanie Plainchault, Bruno Conche, Julien Tierny
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a robust and efficient method for tracking topological features in time-varying scalar data. Structures are tracked based on the optimal matching between persistence diagrams with respect to the Wasserstein metric. This fundamentally relies on solving the assignment problem, a special case of optimal transport, for all consecutive timesteps. Our approach relies on two main contributions. First, we revisit the seminal assignment algorithm by Kuhn and Munkres which we specifically adapt to the problem of matching persistence diagrams in an efficient way. Second, we propose an extension of the Wasserstein metric that significantly improves the geometrical stability of the matching of domain-embedded persistence pairs. We show that this geometrical lifting has the additional positive side-effect of improving the assignment matrix sparsity and therefore computing time. The global framework implements a coarse-grained parallelism by computing persistence diagrams and finding optimal matchings in parallel for every couple of consecutive timesteps. Critical trajectories are constructed by associating successively matched persistence pairs over time. Merging and splitting events are detected with a geometrical threshold in a post-processing stage. Extensive experiments on real-life datasets show that our matching approach is an order of magnitude faster than the seminal Munkres algorithm. Moreover, compared to a modern approximation method, our method provides competitive runtimes while yielding exact results. We demonstrate the utility of our global framework by extracting critical point trajectories from various simulated time-varying datasets and compare it to the existing methods based on associated overlaps of volumes. Robustness to noise and temporal resolution downsampling is empirically demonstrated.

##### Abstract (translated by Google)
本文提出了一种稳健有效的方法来跟踪时变标量数据中的拓扑特征。基于持久性图与Wasserstein度量之间的最佳匹配来跟踪结构。这从根本上依赖于解决分配问题，这是所有连续时间步长的最佳传输的特例。我们的方法依赖于两个主要贡献。首先，我们重新审视Kuhn和Munkres的开创性分配算法，我们特别适应了以有效方式匹配持久性图的问题。其次，我们提出了Wasserstein度量的扩展，它显着提高了域嵌入式持久性对匹配的几何稳定性。我们证明了这种几何提升具有额外的正面副作用，即改善分配矩阵稀疏性并因此改善计算时间。全局框架通过计算持久性图并在每两个连续的时间步长中并行找到最佳匹配来实现粗粒度并行性。通过随时间关联连续匹配的持久性对来构建临界轨迹。在后处理阶段使用几何阈值检测合并和分裂事件。对现实数据集的大量实验表明，我们的匹配方法比开创性的Munkres算法快一个数量级。此外，与现代近似方法相比，我们的方法提供了有竞争力的运行时间，同时产生了精确的结果。我们通过从各种模拟的时变数据集中提取关键点轨迹并将其与基于相关的体积重叠的现有方法进行比较来证明我们的全局框架的效用。根据经验证明了对噪声和时间分辨率下采样的鲁棒性。

##### URL
[http://arxiv.org/abs/1808.05870](http://arxiv.org/abs/1808.05870)

##### PDF
[http://arxiv.org/pdf/1808.05870](http://arxiv.org/pdf/1808.05870)

