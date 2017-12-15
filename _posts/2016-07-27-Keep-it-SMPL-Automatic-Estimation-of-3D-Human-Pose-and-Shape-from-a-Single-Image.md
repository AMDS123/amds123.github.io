---
layout: post
title: "Keep it SMPL: Automatic Estimation of 3D Human Pose and Shape from a Single Image"
date: 2016-07-27 14:46:36
categories: arXiv_CV
tags: arXiv_CV Relation
author: Federica Bogo, Angjoo Kanazawa, Christoph Lassner, Peter Gehler, Javier Romero, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
We describe the first method to automatically estimate the 3D pose of the human body as well as its 3D shape from a single unconstrained image. We estimate a full 3D mesh and show that 2D joints alone carry a surprising amount of information about body shape. The problem is challenging because of the complexity of the human body, articulation, occlusion, clothing, lighting, and the inherent ambiguity in inferring 3D from 2D. To solve this, we first use a recently published CNN-based method, DeepCut, to predict (bottom-up) the 2D body joint locations. We then fit (top-down) a recently published statistical body shape model, called SMPL, to the 2D joints. We do so by minimizing an objective function that penalizes the error between the projected 3D model joints and detected 2D joints. Because SMPL captures correlations in human shape across the population, we are able to robustly fit it to very little data. We further leverage the 3D model to prevent solutions that cause interpenetration. We evaluate our method, SMPLify, on the Leeds Sports, HumanEva, and Human3.6M datasets, showing superior pose accuracy with respect to the state of the art.

##### Abstract (translated by Google)
我们描述了第一种自动估算人体三维姿态的方法，以及一个单一的无约束图像的三维形状。我们估计一个完整的三维网格，并显示单独的二维关节带有关于身体形状的惊人数量的信息。由于人体的复杂性，发音，遮挡，服装，照明以及从2D推断3D的固有模糊性，所以该问题具有挑战性。为了解决这个问题，我们首先使用最近发布的基于CNN的方法DeepCut来预测（自下而上）2D身体关节的位置。然后，我们将（最近发布的）称为SMPL的统计人体形状模型（自上而下）拟合到2D关节。我们通过最小化目标函数来惩罚投影3D模型关节和检测到的2D关节之间的误差。因为SMPL可以捕捉整个人群中人体形状的相关性，所以我们可以很好地将其适用于很少的数据。我们进一步利用3D模型来防止导致相互渗透的解决方案。我们在Leeds Sports，HumanEva和Human3.6M数据集上评估了我们的方法SMPLify，显示出相对于现有技术水平而言卓越的姿态精度。

##### URL
[https://arxiv.org/abs/1607.08128](https://arxiv.org/abs/1607.08128)

##### PDF
[https://arxiv.org/pdf/1607.08128](https://arxiv.org/pdf/1607.08128)

