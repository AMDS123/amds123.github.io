---
layout: post
title: "Bottom-up Pose Estimation of Multiple Person with Bounding Box Constraint"
date: 2018-07-26 06:33:32
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Miaopeng Li, Zimeng Zhou, Jie Li, Xinguo Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a new method for multi-person pose estimation which combines the traditional bottom-up and the top-down methods. Specifically, we perform the network feed-forwarding in a bottom-up manner, and then parse the poses with bounding box constraints in a top-down manner. In contrast to the previous top-down methods, our method is robust to bounding box shift and tightness. We extract features from an original image by a residual network and train the network to learn both the confidence maps of joints and the connection relationships between joints. During testing, the predicted confidence maps, the connection relationships and the bounding boxes are used to parse the poses of all persons. The experimental results showed that our method learns more accurate human poses especially in challenging situations and gains better time performance, compared with the bottom-up and the top-down methods.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种新的多人姿势估计方法，它结合了传统的自下而上和自上而下的方法。具体来说，我们以自下而上的方式执行网络前馈，然后以自上而下的方式解析具有边界框约束的姿势。与之前的自上而下方法相比，我们的方法对于边界框移位和紧密度是稳健的。我们通过残余网络从原始图像中提取特征并训练网络以学习关节的置信度图和关节之间的连接关系。在测试期间，预测的置信度图，连接关系和边界框用于解析所有人的姿势。实验结果表明，与自下而上和自上而下的方法相比，我们的方法可以学习更准确的人体姿势，特别是在具有挑战性的情况下，并获得更好的时间表现。

##### URL
[http://arxiv.org/abs/1807.09972](http://arxiv.org/abs/1807.09972)

##### PDF
[http://arxiv.org/pdf/1807.09972](http://arxiv.org/pdf/1807.09972)

