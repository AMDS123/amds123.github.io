---
layout: post
title: "Robust Face Alignment Using a Mixture of Invariant Experts"
date: 2016-10-23 18:31:06
categories: arXiv_CV
tags: arXiv_CV Face
author: Oncel Tuzel, Tim K. Marks, Salil Tambe
mathjax: true
---

* content
{:toc}

##### Abstract
Face alignment, which is the task of finding the locations of a set of facial landmark points in an image of a face, is useful in widespread application areas. Face alignment is particularly challenging when there are large variations in pose (in-plane and out-of-plane rotations) and facial expression. To address this issue, we propose a cascade in which each stage consists of a mixture of regression experts. Each expert learns a customized regression model that is specialized to a different subset of the joint space of pose and expressions. The system is invariant to a predefined class of transformations (e.g., affine), because the input is transformed to match each expert's prototype shape before the regression is applied. We also present a method to include deformation constraints within the discriminative alignment framework, which makes our algorithm more robust. Our algorithm significantly outperforms previous methods on publicly available face alignment datasets.

##### Abstract (translated by Google)
面部对齐，这是在面部的图像中找到一组面部标志点的位置的任务，在广泛的应用领域中是有用的。当姿势（面内和面外旋转）和面部表情变化很大时，脸部对齐特别具有挑战性。为了解决这个问题，我们提出了一个级联，其中每个阶段由回归专家的混合物组成。每位专家学习一个专门针对姿势和表情的关节空间的不同子集的定制回归模型。该系统对于预定义类别的变换（例如，仿射）是不变的，因为在应用回归之前，输入被变换以匹配每个专家的原型形状。我们还提出了一种方法，在区分对齐框架中包含变形约束，这使得我们的算法更加健壮。我们的算法在公开可用的人脸对齐数据集上显着优于以前的方法。

##### URL
[https://arxiv.org/abs/1511.04404](https://arxiv.org/abs/1511.04404)

##### PDF
[https://arxiv.org/pdf/1511.04404](https://arxiv.org/pdf/1511.04404)

