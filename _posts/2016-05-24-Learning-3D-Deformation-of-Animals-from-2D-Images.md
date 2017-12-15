---
layout: post
title: "Learning 3D Deformation of Animals from 2D Images"
date: 2016-05-24 18:32:58
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Angjoo Kanazawa, Shahar Kovalsky, Ronen Basri, David W. Jacobs
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding how an animal can deform and articulate is essential for a realistic modification of its 3D model. In this paper, we show that such information can be learned from user-clicked 2D images and a template 3D model of the target animal. We present a volumetric deformation framework that produces a set of new 3D models by deforming a template 3D model according to a set of user-clicked images. Our framework is based on a novel locally-bounded deformation energy, where every local region has its own stiffness value that bounds how much distortion is allowed at that location. We jointly learn the local stiffness bounds as we deform the template 3D mesh to match each user-clicked image. We show that this seemingly complex task can be solved as a sequence of convex optimization problems. We demonstrate the effectiveness of our approach on cats and horses, which are highly deformable and articulated animals. Our framework produces new 3D models of animals that are significantly more plausible than methods without learned stiffness.

##### Abstract (translated by Google)
了解一个动物如何变形和清晰表达对于3D模型的真实修改至关重要。在本文中，我们展示了这样的信息可以从用户点击的2D图像和目标动物的模板3D模型中学习。我们提出了一个体积变形框架，通过根据一组用户点击的图像变形模板3D模型来产生一组新的3D模型。我们的框架基于一种新颖的局部有界变形能量，其中每个局部区域都有其自己的刚度值，该刚度值限定了在该位置处允许多少变形。我们联合学习局部刚度边界，因为我们变形模板3D网格以匹配每个用户点击的图像。我们证明这个看似复杂的任务可以被解决为一系列的凸优化问题。我们展示了我们的方法对猫和马，这是高度变形和铰接动物的有效性。我们的框架产生新的3D动物模型，比没有学习刚度的方法显得更有说服力。

##### URL
[https://arxiv.org/abs/1507.07646](https://arxiv.org/abs/1507.07646)

##### PDF
[https://arxiv.org/pdf/1507.07646](https://arxiv.org/pdf/1507.07646)

