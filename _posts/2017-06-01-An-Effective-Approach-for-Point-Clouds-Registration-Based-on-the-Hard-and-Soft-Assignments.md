---
layout: post
title: "An Effective Approach for Point Clouds Registration Based on the Hard and Soft Assignments"
date: 2017-06-01 09:31:04
categories: arXiv_CV
tags: arXiv_CV
author: Congcong Jin, Jihua Zhu, Yaochen Li, Shaoyi Du, Zhongyu Li, Huimin Lu
mathjax: true
---

* content
{:toc}

##### Abstract
For the registration of partially overlapping point clouds, this paper proposes an effective approach based on both the hard and soft assignments. Given two initially posed clouds, it firstly establishes the forward correspondence for each point in the data shape and calculates the value of binary variable, which can indicate whether this point correspondence is located in the overlapping areas or not. Then, it establishes the bilateral correspondence and computes bidirectional distances for each point in the overlapping areas. Based on the ratio of bidirectional distances, the exponential function is selected and utilized to calculate the probability value, which can indicate the reliability of the point correspondence. Subsequently, both the values of hard and soft assignments are embedded into the proposed objective function for registration of partially overlapping point clouds and a novel variant of ICP algorithm is proposed to obtain the optimal rigid transformation. The proposed approach can achieve good registration of point clouds, even when their overlap percentage is low. Experimental results tested on public data sets illustrate its superiority over previous approaches on accuracy and robustness.

##### Abstract (translated by Google)
对于部分重叠点云的注册，本文提出了一种基于软硬配置的有效方法。给定两个初始云，首先建立数据形状中每个点的前向对应关系，并计算二进制变量的值，表明该点对应关系是否位于重叠区域。然后，建立双边对应关系，并计算重叠区域中每个点的双向距离。根据双向距离的比值选择指数函数计算概率值，可以指示点对应的可靠性。随后将软硬指派值嵌入到部分重叠点云的配准目标函数中，提出了一种新的ICP算法变体，以获得最优的刚性变换。所提出的方法可以实现点云的良好配准，即使它们的重叠百分比较低。在公共数据集上测试的实验结果说明其在精度和稳健性方面优于以前的方法。

##### URL
[https://arxiv.org/abs/1706.00227](https://arxiv.org/abs/1706.00227)

##### PDF
[https://arxiv.org/pdf/1706.00227](https://arxiv.org/pdf/1706.00227)

