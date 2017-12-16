---
layout: post
title: "Joint Large-Scale Motion Estimation and Image Reconstruction"
date: 2016-10-31 13:16:38
categories: arXiv_CV
tags: arXiv_CV
author: Hendrik Dirks
mathjax: true
---

* content
{:toc}

##### Abstract
This article describes the implementation of the joint motion estimation and image reconstruction framework presented by Burger, Dirks and Sch\"onlieb and extends this framework to large-scale motion between consecutive image frames. The variational framework uses displacements between consecutive frames based on the optical flow approach to improve the image reconstruction quality on the one hand and the motion estimation quality on the other. The energy functional consists of a data-fidelity term with a general operator that connects the input sequence to the solution, it has a total variation term for the image sequence and is connected to the underlying flow using an optical flow term. Additional spatial regularity for the flow is modeled by a total variation regularizer for both components of the flow. The numerical minimization is performed in an alternating manner using primal-dual techniques. The resulting schemes are presented as pseudo-code together with a short numerical evaluation.

##### Abstract (translated by Google)
本文介绍了由Burger，Dirks和Schneib提出的联合运动估计和图像重构框架的实现，并将该框架扩展到连续图像帧之间的大规模运动，变分框架使用基于光学的连续帧之间的位移一方面提高图像重建质量，另一方面提高运动估计的质量;能量函数由一个数据保真项和一个通用算子组成，它将输入序列连接到解，它有一个总变差项对于图像序列，并使用光学流量项将其连接到下面的流量，对于流量的另外的空间规律性由流量的两个分量的总变化规则化模型进行建模，数值最小化以交替的方式使用原始对偶所得到的方案以伪代码的形式与简短的数字eva一起呈现luation。

##### URL
[https://arxiv.org/abs/1610.09908](https://arxiv.org/abs/1610.09908)

##### PDF
[https://arxiv.org/pdf/1610.09908](https://arxiv.org/pdf/1610.09908)

