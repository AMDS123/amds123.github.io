---
layout: post
title: "Enhanced Mixtures of Part Model for Human Pose Estimation"
date: 2015-01-28 08:16:55
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization Detection Relation
author: Wenjuan Gong, Yongzhen Huang, Jordi Gonzalez, and Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Mixture of parts model has been successfully applied to 2D human pose estimation problem either as explicitly trained body part model or as latent variables for the whole human body model. Mixture of parts model usually utilize tree structure for representing relations between body parts. Tree structures facilitate training and referencing of the model but could not deal with double counting problems, which hinder its applications in 3D pose estimation. While most of work targeted to solve these problems tend to modify the tree models or the optimization target. We incorporate other cues from input features. For example, in surveillance environments, human silhouettes can be extracted relative easily although not flawlessly. In this condition, we can combine extracted human blobs with histogram of gradient feature, which is commonly used in mixture of parts model for training body part templates. The method can be easily extend to other candidate features under our generalized framework. We show 2D body part detection results on a public available dataset: HumanEva dataset. Furthermore, a 2D to 3D pose estimator is trained with Gaussian process regression model and 2D body part detections from the proposed method is fed to the estimator, thus 3D poses are predictable given new 2D body part detections. We also show results of 3D pose estimation on HumanEva dataset.

##### Abstract (translated by Google)
零件模型的混合已被成功地应用于二维人体姿态估计问题，既可以作为明确训练的身体部位模型，也可以作为整个人体模型的潜在变量。零件模型的组合通常利用树形结构来表示身体部位之间的关系。树结构有利于模型的训练和引用，但不能处理重复计算的问题，阻碍了其在三维姿态估计中的应用。虽然大多数解决这些问题的工作倾向于修改树模型或优化目标。我们结合输入功能的其他线索。例如，在监视环境中，人的轮廓可以相对容易地提取，尽管并不完美。在这种情况下，我们可以将提取出的人体斑点与梯度特征直方图结合起来，这在训练身体局部模板的零件模型混合中是常用的。该方法可以很容易地扩展到我们的广义框架下的其他候选特征。我们在一个公开的可用数据集上显示2D身体部位检测结果：HumanEva数据集。此外，用高斯过程回归模型训练2D到3D姿态估计器，并且将所提出的方法的2D身体部位检测馈送到估计器，从而在给定新的2D身体部位检测的情况下3D姿态是可预测的。我们还显示了HumanEva数据集上的三维姿态估计结果。

##### URL
[https://arxiv.org/abs/1501.05382](https://arxiv.org/abs/1501.05382)

##### PDF
[https://arxiv.org/pdf/1501.05382](https://arxiv.org/pdf/1501.05382)

