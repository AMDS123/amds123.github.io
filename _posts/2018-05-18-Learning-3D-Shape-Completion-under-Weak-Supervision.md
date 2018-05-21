---
layout: post
title: "Learning 3D Shape Completion under Weak Supervision"
date: 2018-05-18 15:37:28
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: David Stutz, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of 3D shape completion from sparse and noisy point clouds, a fundamental problem in computer vision and robotics. Recent approaches are either data-driven or learning-based: Data-driven approaches rely on a shape model whose parameters are optimized to fit the observations; Learning-based approaches, in contrast, avoid the expensive optimization step by learning to directly predict complete shapes from incomplete observations in a fully-supervised setting. However, full supervision is often not available in practice. In this work, we propose a weakly-supervised learning-based approach to 3D shape completion which neither requires slow optimization nor direct supervision. While we also learn a shape prior on synthetic data, we amortize, i.e., learn, maximum likelihood fitting using deep neural networks resulting in efficient shape completion without sacrificing accuracy. On synthetic benchmarks based on ShapeNet and ModelNet as well as on real robotics data from KITTI and Kinect, we demonstrate that the proposed amortized maximum likelihood approach is able to compete with the fully supervised baseline of and outperforms the data-driven approach of, while requiring less supervision and being significantly faster.

##### Abstract (translated by Google)
我们解决了稀疏和有噪点云的三维形状完成问题，这是计算机视觉和机器人技术中的一个基本问题。最近的方法或者是数据驱动的，或者是基于学习的：数据驱动的方法依赖于一个形状模型，其参数被优化以适应观察;相比之下，基于学习的方法避免了昂贵的优化步骤，通过学习直接预测完全监督环境下不完整观测的完整形状。但是，在实践中往往没有全面的监督。在这项工作中，我们提出了一种弱监督的基于学习的3D形状完成方法，既不需要缓慢的优化，也不需要直接的监督。虽然我们也在合成数据之前学习了一个形状，但是我们摊销，即学习使用深度神经网络的最大似然拟合，从而导致高效的形状完成而不牺牲准确性。在基于ShapeNet和ModelNet的综合基准以及来自KITTI和Kinect的真实机器人数据上，我们证明拟议的摊销最大似然法能够与完全监督的基线竞争，并且胜过数据驱动的方法，同时要求更少的监督和明显更快。

##### URL
[http://arxiv.org/abs/1805.07290](http://arxiv.org/abs/1805.07290)

##### PDF
[http://arxiv.org/pdf/1805.07290](http://arxiv.org/pdf/1805.07290)

