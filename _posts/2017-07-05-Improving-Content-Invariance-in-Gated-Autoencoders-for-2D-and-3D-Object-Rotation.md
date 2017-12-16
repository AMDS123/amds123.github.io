---
layout: post
title: "Improving Content-Invariance in Gated Autoencoders for 2D and 3D Object Rotation"
date: 2017-07-05 12:28:43
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Relation
author: Stefan Lattner, Maarten Grachten
mathjax: true
---

* content
{:toc}

##### Abstract
Content-invariance in mapping codes learned by GAEs is a useful feature for various relation learning tasks. In this paper we show that the content-invariance of mapping codes for images of 2D and 3D rotated objects can be substantially improved by extending the standard GAE loss (symmetric reconstruction error) with a regularization term that penalizes the symmetric cross-reconstruction error. This error term involves reconstruction of pairs with mapping codes obtained from other pairs exhibiting similar transformations. Although this would principally require knowledge of the transformations exhibited by training pairs, our experiments show that a bootstrapping approach can sidestep this issue, and that the regularization term can effectively be used in an unsupervised setting.

##### Abstract (translated by Google)
由GAE学习的映射代码中的内容不变性是各种关系学习任务的有用特征。在本文中，我们表明，2D和3D旋转物体的图像的映射代码的内容不变性可以通过用正则化术语来扩展标准GAE损失（对称重构误差）而大大提高，所述正则化术语惩罚对称交叉重建误差。这个误差项涉及用从其他展现相似变换的对获得的映射代码重构对。虽然这主要需要知道训练对所展示的变换，但是我们的实验表明，自举法可以回避这个问题，并且正则化术语可以有效地用于无监督的设置。

##### URL
[https://arxiv.org/abs/1707.01357](https://arxiv.org/abs/1707.01357)

##### PDF
[https://arxiv.org/pdf/1707.01357](https://arxiv.org/pdf/1707.01357)

