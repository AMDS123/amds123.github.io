---
layout: post
title: "Shape Generation using Spatially Partitioned Point Clouds"
date: 2017-07-19 19:32:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Quantitative
author: Matheus Gadelha, Subhransu Maji, Rui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to generate 3D shapes using point clouds. Given a point-cloud representation of a 3D shape, our method builds a kd-tree to spatially partition the points. This orders them consistently across all shapes, resulting in reasonably good correspondences across all shapes. We then use PCA analysis to derive a linear shape basis across the spatially partitioned points, and optimize the point ordering by iteratively minimizing the PCA reconstruction error. Even with the spatial sorting, the point clouds are inherently noisy and the resulting distribution over the shape coefficients can be highly multi-modal. We propose to use the expressive power of neural networks to learn a distribution over the shape coefficients in a generative-adversarial framework. Compared to 3D shape generative models trained on voxel-representations, our point-based method is considerably more light-weight and scalable, with little loss of quality. It also outperforms simpler linear factor models such as Probabilistic PCA, both qualitatively and quantitatively, on a number of categories from the ShapeNet dataset. Furthermore, our method can easily incorporate other point attributes such as normal and color information, an additional advantage over voxel-based representations.

##### Abstract (translated by Google)
我们提出一种使用点云来生成三维形状的方法。给定一个三维形状的点云表示，我们的方法建立一个kd树来空间分割点。这使得它们在所有形状上都一致，从而在所有形状上产生了相当好的对应关系。然后，我们使用PCA分析在空间分割点上导出线性形状基础，并通过迭代地最小化PCA重建误差来优化点排序。即使在空间排序的情况下，点云本身也是嘈杂的，并且由此产生的形状系数分布可以是高度多模式的。我们建议使用神经网络的表现力来学习生成对抗框架中形状系数的分布。与在体素表示上训练的3D形状生成模型相比，我们基于点的方法明显更轻量且可扩展，质量损失很小。它也比ShapeNet数据集的多个类别在性能和数量上都优于简单的线性因子模型，如概率PCA。此外，我们的方法可以很容易地结合其他点属性，如法线和颜色信息，这是基于体素的表示的一个额外的优势。

##### URL
[https://arxiv.org/abs/1707.06267](https://arxiv.org/abs/1707.06267)

##### PDF
[https://arxiv.org/pdf/1707.06267](https://arxiv.org/pdf/1707.06267)

