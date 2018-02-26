---
layout: post
title: "Locally Adaptive Learning Loss for Semantic Image Segmentation"
date: 2018-02-23 05:18:35
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction
author: Jinjiang Guo, Pengyuan Ren, Aiguo Gu, Jian Xu, Weixin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel locally adaptive learning estimator for enhancing the inter- and intra- discriminative capabilities of Deep Neural Networks, which can be used as improved loss layer for semantic image segmentation tasks. Most loss layers compute pixel-wise cost between feature maps and ground truths, ignoring spatial layouts and interactions between neighboring pixels with same object category, and thus networks cannot be effectively sensitive to intra-class connections. Stride by stride, our method firstly conducts adaptive pooling filter operating over predicted feature maps, aiming to merge predicted distributions over a small group of neighboring pixels with same category, and then computes cost between the merged distribution vector and their category label. Such design can make groups of neighboring predictions from same category involved into estimations on predicting correctness with respect to their category, and hence train networks to be more sensitive to regional connections between adjacent pixels based on their categories. In the experiments on Pascal VOC 2012 segmentation datasets, the consistently improved results show that our proposed approach achieves better segmentation masks against previous counterparts.

##### Abstract (translated by Google)
我们提出了一种新颖的局部自适应学习估计器，用于增强深度神经网络的内部和内部判别能力，可以将其用作语义图像分割任务的改进损失层。大多数损失层计算特征映射和地面实况之间的像素成本，忽略具有相同对象类别的相邻像素之间的空间布局和相互作用，因此网络无法对类内连接有效敏感。我们的方法首先在预测的特征映射上进行自适应池化滤波，其目标是将相同类别的相邻像素的小群组上的预测分布合并，然后计算合并分布矢量与其类别标签之间的成本。这样的设计可以使来自相同类别的相邻预测组成预测关于其类别的正确性的估计，并且因此训练网络基于它们的类别对相邻像素之间的区域连接更敏感。在Pascal VOC 2012分割数据集的实验中，持续改进的结果表明，我们提出的方法实现了比以前更好的分割掩模。

##### URL
[http://arxiv.org/abs/1802.08290](http://arxiv.org/abs/1802.08290)

##### PDF
[http://arxiv.org/pdf/1802.08290](http://arxiv.org/pdf/1802.08290)

