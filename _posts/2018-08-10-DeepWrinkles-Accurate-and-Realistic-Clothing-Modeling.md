---
layout: post
title: "DeepWrinkles: Accurate and Realistic Clothing Modeling"
date: 2018-08-10 05:45:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Face
author: Zorah Laehner, Daniel Cremers, Tony Tung
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel method to generate accurate and realistic clothing deformation from real data capture. Previous methods for realistic cloth modeling mainly rely on intensive computation of physics-based simulation (with numerous heuristic parameters), while models reconstructed from visual observations typically suffer from lack of geometric details. Here, we propose an original framework consisting of two modules that work jointly to represent global shape deformation as well as surface details with high fidelity. Global shape deformations are recovered from a subspace model learned from 3D data of clothed people in motion, while high frequency details are added to normal maps created using a conditional Generative Adversarial Network whose architecture is designed to enforce realism and temporal consistency. This leads to unprecedented high-quality rendering of clothing deformation sequences, where fine wrinkles from (real) high resolution observations can be recovered. In addition, as the model is learned independently from body shape and pose, the framework is suitable for applications that require retargeting (e.g., body animation). Our experiments show original high quality results with a flexible model. We claim an entirely data-driven approach to realistic cloth wrinkle generation is possible.

##### Abstract (translated by Google)
我们提出了一种新方法，通过实际数据捕获生成准确和逼真的服装变形。以前用于逼真布料建模的方法主要依赖于基于物理的模拟的密集计算（具有许多启发式参数），而从视觉观察重建的模型通常缺乏几何细节。在这里，我们提出了一个由两个模块组成的原始框架，这两个模块共同工作以表示全局形状变形以及高保真度的表面细节。全局形状变形从从运动中穿着衣服的人的3D数据中学习的子空间模型中恢复，而高频细节被添加到使用条件生成对抗网络创建的法线地图，其结构被设计为强制逼真和时间一致性。这导致衣物变形序列的前所未有的高质量渲染，其中可以恢复来自（真实）高分辨率观察的细皱纹。此外，由于模型是独立于身体形状和姿势学习的，因此该框架适用于需要重新定位（例如，身体动画）的应用。我们的实验通过灵活的模型显示原始的高质量结果。我们声称采用完全数据驱动的方法来实现真实的皱纹生成。

##### URL
[http://arxiv.org/abs/1808.03417](http://arxiv.org/abs/1808.03417)

##### PDF
[http://arxiv.org/pdf/1808.03417](http://arxiv.org/pdf/1808.03417)

