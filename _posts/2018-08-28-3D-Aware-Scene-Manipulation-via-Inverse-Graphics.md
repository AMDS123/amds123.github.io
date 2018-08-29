---
layout: post
title: "3D-Aware Scene Manipulation via Inverse Graphics"
date: 2018-08-28 15:16:07
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Shunyu Yao, Tzu Ming Harry Hsu, Jun-Yan Zhu, Jiajun Wu, Antonio Torralba, Bill Freeman, Joshua Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
We aim to obtain an interpretable, expressive and disentangled scene representation that contains comprehensive structural and textural information for each object. Previous representations learned by neural networks are often uninterpretable, limited to a single object, or lack 3D knowledge. In this work, we address the above issues by integrating 3D modeling into a deep generative model. We adopt a differentiable shape renderer to decode geometrical object attributes into a shape, and a neural generator to decode learned latent codes to texture. The encoder is therefore forced to perform an inverse graphics task and transform a scene image into a structured representation with 3D attributes of objects and learned texture latent codes. The representation supports reconstruction and a variety of 3D-aware scene manipulation applications. The disentanglement of structure and texture in our representation allows us to rotate and move objects freely while maintaining consistent texture, as well as changing the object appearance without affecting their structures. We systematically evaluate our representation and demonstrate that our editing scheme is superior to 2D counterparts.

##### Abstract (translated by Google)
我们的目标是获得一个可解释的，富有表现力的和解开的场景表示，其中包含每个对象的综合结构和纹理信息。以前通过神经网络学习的表示通常是无法解释的，仅限于单个对象，或缺乏3D知识。在这项工作中，我们通过将3D建模集成到深度生成模型中来解决上述问题。我们采用可微分的形状渲染器将几何对象属性解码为形状，并使用神经生成器将学习的潜在代码解码为纹理。因此，编码器被迫执行逆图形任务并将场景图像变换为具有对象的3D属性和学习的纹理潜码的结构化表示。该表示支持重建和各种3D感知场景操纵应用。在我们的表示中解构结构和纹理允许我们自由地旋转和移动物体，同时保持一致的纹理，以及改变物体外观而不影响它们的结构。我们系统地评估我们的表示，并证明我们的编辑方案优于2D对应物。

##### URL
[http://arxiv.org/abs/1808.09351](http://arxiv.org/abs/1808.09351)

##### PDF
[http://arxiv.org/pdf/1808.09351](http://arxiv.org/pdf/1808.09351)

