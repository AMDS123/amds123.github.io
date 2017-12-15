---
layout: post
title: "Branching Gaussian Processes with Applications to Spatiotemporal Reconstruction of 3D Trees"
date: 2016-08-14 01:41:07
categories: arXiv_CV
tags: arXiv_CV Attention Inference
author: Kyle Simek, Ravishankar Palanivelu, Kobus Barnard
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a robust method for estimating dynamic 3D curvilinear branching structure from monocular images. While 3D reconstruction from images has been widely studied, estimating thin structure has received less attention. This problem becomes more challenging in the presence of camera error, scene motion, and a constraint that curves are attached in a branching structure. We propose a new general-purpose prior, a branching Gaussian processes (BGP), that models spatial smoothness and temporal dynamics of curves while enforcing attachment between them. We apply this prior to fit 3D trees directly to image data, using an efficient scheme for approximate inference based on expectation propagation. The BGP prior's Gaussian form allows us to approximately marginalize over 3D trees with a given model structure, enabling principled comparison between tree models with varying complexity. We test our approach on a novel multi-view dataset depicting plants with known 3D structures and topologies undergoing small nonrigid motion. Our method outperforms a state-of-the-art 3D reconstruction method designed for non-moving thin structure. We evaluate under several common measures, and we propose a new measure for reconstructions of branching multi-part 3D scenes under motion.

##### Abstract (translated by Google)
我们提出了一个强大的方法来估计单眼图像的动态三维曲线分支结构。虽然从图像的三维重建已经被广泛研究，估计薄结构已经受到较少的关注。在存在相机错误，场景运动和曲线附加在分支结构中的限制的情况下，这个问题变得更具挑战性。我们提出了一种新的通用先验分支高斯过程（BGP），该过程对曲线的空间平滑度和时间动态进行建模，同时强化它们之间的连接。我们应用这之前，拟合三维树直接图像数据，使用一个有效的方案进行近似推理的期望传播。 BGP先验的高斯形式允许我们近似边缘化具有给定模型结构的3D树，使得具有不同复杂度的树模型之间的原则性比较成为可能。我们测试我们的方法在一个新颖的多视图数据集描绘植物与已知的三维结构和拓扑结构接受小非刚性运动。我们的方法胜过了为不移动的薄结构设计的最先进的三维重建方法。我们在几个常见的措施下进行评估，并提出了一种新的分支多部分3D场景重建的方法。

##### URL
[https://arxiv.org/abs/1608.04045](https://arxiv.org/abs/1608.04045)

##### PDF
[https://arxiv.org/pdf/1608.04045](https://arxiv.org/pdf/1608.04045)

