---
layout: post
title: "Motion-based Object Segmentation based on Dense RGB-D Scene Flow"
date: 2018-07-24 08:49:35
categories: arXiv_RO
tags: arXiv_RO Segmentation Quantitative Relation
author: Lin Shao, Parth Shah, Vikranth Dwaracherla, Jeannette Bohg
mathjax: true
---

* content
{:toc}

##### Abstract
Given two consecutive RGB-D images, we propose a model that estimates a dense 3D motion field, also known as scene flow. We take advantage of the fact that in robot manipulation scenarios, scenes often consist of a set of rigidly moving objects. Our model jointly estimates (i) the segmentation of the scene into an unknown but finite number of objects, (ii) the motion trajectories of these objects and (iii) the object scene flow. We employ an hourglass, deep neural network architecture. In the encoding stage, the RGB and depth images undergo spatial compression and correlation. In the decoding stage, the model outputs three images containing a per-pixel estimate of the corresponding object center as well as object translation and rotation. This forms the basis for inferring the object segmentation and final object scene flow. To evaluate our model, we generated a new and challenging, large-scale, synthetic dataset that is specifically targeted at robotic manipulation: It contains a large number of scenes with a very diverse set of simultaneously moving 3D objects and is recorded with a simulated, static RGB-D camera. In quantitative experiments, we show that we outperform state-of-the-art scene flow and motion-segmentation methods on this data set. In qualitative experiments, we show how our learned model transfers to challenging real-world scenes, visually generating better results than existing methods.

##### Abstract (translated by Google)
给定两个连续的RGB-D图像，我们提出了一种估计密集的3D运动场的模型，也称为场景流。我们利用这样的事实：在机器人操纵场景中，场景通常由一组刚性移动的物体组成。我们的模型联合估计（i）将场景分割成未知但有限数量的对象，（ii）这些对象的运动轨迹和（iii）对象场景流。我们采用沙漏，深度神经网络架构。在编码阶段，RGB和深度图像经历空间压缩和相关。在解码阶段，模型输出三个图像，其包含相应对象中心的每像素估计以及对象平移和旋转。这形成了推断对象分割和最终对象场景流的基础。为了评估我们的模型，我们生成了一个新的，具有挑战性的，大规模的合成数据集，专门针对机器人操作：它包含大量具有多种同时移动的3D对象的场景，并使用模拟记录，静态RGB-D相机。在定量实验中，我们表明我们在这个数据集上优于最先进的场景流和运动分割方法。在定性实验中，我们展示了我们的学习模型如何转移到具有挑战性的真实场景，在视觉上产生比现有方法更好的结果。

##### URL
[http://arxiv.org/abs/1804.05195](http://arxiv.org/abs/1804.05195)

##### PDF
[http://arxiv.org/pdf/1804.05195](http://arxiv.org/pdf/1804.05195)

