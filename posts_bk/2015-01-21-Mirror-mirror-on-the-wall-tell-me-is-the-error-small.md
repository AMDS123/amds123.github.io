---
layout: post
title: "Mirror, mirror on the wall, tell me, is the error small?"
date: 2015-01-21 12:22:38
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Pose_Estimation Detection Relation
author: Heng Yang, Ioannis Patras
mathjax: true
---

* content
{:toc}

##### Abstract
Do object part localization methods produce bilaterally symmetric results on mirror images? Surprisingly not, even though state of the art methods augment the training set with mirrored images. In this paper we take a closer look into this issue. We first introduce the concept of mirrorability as the ability of a model to produce symmetric results in mirrored images and introduce a corresponding measure, namely the \textit{mirror error} that is defined as the difference between the detection result on an image and the mirror of the detection result on its mirror image. We evaluate the mirrorability of several state of the art algorithms in two of the most intensively studied problems, namely human pose estimation and face alignment. Our experiments lead to several interesting findings: 1) Surprisingly, most of state of the art methods struggle to preserve the mirror symmetry, despite the fact that they do have very similar overall performance on the original and mirror images; 2) the low mirrorability is not caused by training or testing sample bias - all algorithms are trained on both the original images and their mirrored versions; 3) the mirror error is strongly correlated to the localization/alignment error (with correlation coefficients around 0.7). Since the mirror error is calculated without knowledge of the ground truth, we show two interesting applications - in the first it is used to guide the selection of difficult samples and in the second to give feedback in a popular Cascaded Pose Regression method for face alignment.

##### Abstract (translated by Google)
对象部分定位方法是否对镜像产生双边对称结果？令人惊讶的是，即使最先进的方法用镜像图像来增强训练集。在本文中，我们仔细研究这个问题。我们首先引入了镜像的概念作为模型在镜像中产生对称结果的能力，并引入了相应的度量，即定义为镜像检测结果与镜像之间差异的\ textit {镜像错误}的镜像上的检测结果。我们在两个最深入研究的问题中评估了几种最先进的算法的可反映性，即人体姿态估计和人脸对齐。我们的实验导致了一些有趣的发现：1）令人惊讶的是，大多数最先进的方法努力保持镜像对称性，尽管事实上它们在原始镜像和镜像上具有非常相似的整体性能; 2）低的可反映性不是由训练或测试样本偏差引起的 - 所有算法都在原始图像和镜像版本上进行训练; 3）镜像误差与定位/对准误差强相关（相关系数在0.7左右）。由于镜像误差是在不知道基本事实的情况下计算出来的，因此我们展示了两个有趣的应用 - 首先用于指导困难样本的选择，然后用流行的级联姿态回归方法给出反馈用于面对齐。

##### URL
[https://arxiv.org/abs/1501.05152](https://arxiv.org/abs/1501.05152)

##### PDF
[https://arxiv.org/pdf/1501.05152](https://arxiv.org/pdf/1501.05152)

