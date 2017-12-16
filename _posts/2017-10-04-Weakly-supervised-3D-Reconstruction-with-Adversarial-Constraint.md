---
layout: post
title: "Weakly supervised 3D Reconstruction with Adversarial Constraint"
date: 2017-10-04 05:45:38
categories: arXiv_CV
tags: arXiv_CV Adversarial Weakly_Supervised GAN Optimization
author: JunYoung Gwak, Christopher B. Choy, Animesh Garg, Manmohan Chandraker, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised 3D reconstruction has witnessed a significant progress through the use of deep neural networks. However, this increase in performance requires large scale annotations of 2D/3D data. In this paper, we explore inexpensive 2D supervision as an alternative for expensive 3D CAD annotation. Specifically, we use foreground masks as weak supervision through a raytrace pooling layer that enables perspective projection and backpropagation. Additionally, since the 3D reconstruction from masks is an ill posed problem, we propose to constrain the 3D reconstruction to the manifold of unlabeled realistic 3D shapes that match mask observations. We demonstrate that learning a log-barrier solution to this constrained optimization problem resembles the GAN objective, enabling the use of existing tools for training GANs. We evaluate and analyze the manifold constrained reconstruction on various datasets for single and multi-view reconstruction of both synthetic and real images.

##### Abstract (translated by Google)
通过使用深度神经网络，监督3D重建已经取得了显着进展。但是，性能的提高需要2D / 3D数据的大规模注释。在本文中，我们探索低成本的2D监视作为昂贵的3D CAD注释的替代方案。具体而言，我们使用前景蒙板作为弱监督，通过光线追踪池层进行透视投影和反向传播。此外，由于面罩的三维重建是一个病态问题，我们建议将三维重建限制在与面罩观察相匹配的未标记真实三维形状的流形。我们证明，学习对这个约束优化问题的对数屏障解决方案类似于GAN目标，使用现有的工具来训练GAN。我们评估和分析了各种数据集上的流形约束重建，用于合成和真实图像的单视图和多视图重构。

##### URL
[https://arxiv.org/abs/1705.10904](https://arxiv.org/abs/1705.10904)

##### PDF
[https://arxiv.org/pdf/1705.10904](https://arxiv.org/pdf/1705.10904)

